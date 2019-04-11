<template>
  <div style="margin: 20px;">
    <el-date-picker
        v-model="value1"
        type="daterange"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
    <el-date-picker
        v-model="value1"
        type="date"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
    <el-date-picker
        v-model="value1"
        type="datetimerange"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
    <el-date-picker
        v-model="value1"
        type="year"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
    <el-date-picker
        v-model="value1"
        type="month"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
    <el-date-picker
        v-model="value1"
        type="dates"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
    <el-date-picker
        v-model="value1"
        type="datetime"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
    <el-date-picker
        v-model="value1"
        type="week"
        :signDays="seleArr"
        placeholder="选择日期">
    </el-date-picker>
    <br>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        value1: '',
        seleArr: ['2019-03-03','2019-04-04','2019-04-07']
      };
    }
  };
</script>
