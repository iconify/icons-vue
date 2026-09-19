<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="o_tgn_b-c"/><path class="xw0d2gynp"/><circle class="rub8z5ice"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:glowline" /></template>
<style>
.o_tgn_b-c {
  cx: 32.745px;
  cy: 35.973px;
  r: 6.042px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rub8z5ice {
  cx: 15.146px;
  cy: 35.973px;
  r: 6.042px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xw0d2gynp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.253 5.984c3.735 2.559 4.22 4.776 4.852 7.437c.763-2.84 1.073-4.98 4.881-7.437m-2.283 29.989V19.497c.286-5.73 4.523-7.921 7.603-7.89c4.148.041 8.11 2.569 8.192 7.225c.17 9.679-9.753 11.098-9.753 11.098m-11.557 6.043V19.74c-.101-4.969-3.686-8.072-7.799-8.132c-3.337-.05-7.902 2.612-7.89 8.495c.017 7.723 9.647 9.828 9.647 9.828");
}

</style>
