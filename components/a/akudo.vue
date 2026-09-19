<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zrz621bse"/><path class="ohfx7e__b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:akudo" /></template>
<style>
.ohfx7e__b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 11.496l-9.905 8.977L24 34.58l9.905-14.107zM24 3.5v41");
}

.zrz621bse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5L5.273 20.473h37.454zm18.727 16.973L24 44.5L5.273 20.473");
}

</style>
