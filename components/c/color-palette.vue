<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ugn9-lbzm"/><circle class="nxrwn568m"/><path class="sqxvbrt2q"/><path class="g9w5g767q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:color-palette" /></template>
<style>
.g9w5g767q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15 42.5A9.5 9.5 0 0 1 5.5 33V7.5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v2.565m-9.5 9.5V5.5m-9.5 9.742h13.823");
}

.nxrwn568m {
  cx: 15px;
  cy: 33px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sqxvbrt2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 33H5.504M18.5 33h24m-19.742 9.5v-19m10 0v19M8.283 39.718a9.5 9.5 0 0 1 0-13.436l18.03-18.03a2 2 0 0 1 2.83 0l10.606 10.606a2 2 0 0 1 0 2.828L37.935 23.5m-13.435 0l9.945-9.945m-13.606.171l9.774 9.774");
}

.ugn9-lbzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15 23.5h25.5a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2H15c-5.243 0-9.5-4.257-9.5-9.5s4.257-9.5 9.5-9.5");
}

</style>
