<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fo3qmbbut"/><circle class="wd9i8zbsg"/><path class="ytjad3_tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flashacademy" /></template>
<style>
.fo3qmbbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 4.5h14a5.5 5.5 0 0 1 5.5 5.5h0a5.5 5.5 0 0 1-5.5 5.5H17a5.5 5.5 0 0 1-5.5-5.5h0A5.5 5.5 0 0 1 17 4.5");
}

.wd9i8zbsg {
  cx: 31px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ytjad3_tv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 18.5a5.5 5.5 0 0 1 5.5 5.5v14a5.5 5.5 0 0 1-5.5 5.5h0a5.5 5.5 0 0 1-5.5-5.5V24a5.5 5.5 0 0 1 5.5-5.5");
}

</style>
