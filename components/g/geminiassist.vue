<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x4v-opb2j"/><path class="sh9n9mb1m"/><circle class="g1lg4046i"/><circle class="dep47ybkb"/><circle class="ei_p_jbbp"/><circle class="gksobsb3j"/><path class="bp1iohx8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geminiassist" /></template>
<style>
.bp1iohx8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.82 27.17l-2.99-2.77m-1.32-1.23l-3.46-3.21");
}

.dep47ybkb {
  cx: 23.668px;
  cy: 33.998px;
  r: 0.75px;
  fill: currentColor;
}

.ei_p_jbbp {
  cx: 28.384px;
  cy: 14.643px;
  r: 0.75px;
  fill: currentColor;
}

.g1lg4046i {
  cx: 13.398px;
  cy: 26.46px;
  r: 0.75px;
  fill: currentColor;
}

.gksobsb3j {
  cx: 25.178px;
  cy: 23.772px;
  r: 0.909px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sh9n9mb1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.919 17.192c.003.12-2.726.961-2.809 1.048c-.082.088-.768 2.86-.888 2.864c-.12.003-.961-2.727-1.048-2.809s-2.86-.769-2.863-.888c-.004-.12 2.726-.961 2.808-1.049s.769-2.86.889-2.863s.96 2.726 1.048 2.809c.087.082 2.86.768 2.863.888m14.304 12.466c.004.131-2.726 1.05-2.808 1.145c-.083.095-.769 3.121-.889 3.125s-.96-2.976-1.048-3.066c-.087-.09-2.86-.839-2.863-.97c-.003-.13 2.726-1.049 2.808-1.144c.083-.095.77-3.121.889-3.125c.12-.004.961 2.976 1.048 3.066s2.86.839 2.863.97");
}

.x4v-opb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.962 5.777h6.076A15.43 15.43 0 0 1 42.5 21.239v3.705a15.43 15.43 0 0 1-15.462 15.462h-6.076c-1.902 0-5.941-.819-5.941-.819l-8.805 2.636l1.122-9.939S5.5 27.604 5.5 24.944V21.24A15.43 15.43 0 0 1 20.962 5.777");
}

</style>
