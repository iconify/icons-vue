<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mf5roac8n"/><circle class="f_4ku1ico"/><path class="yz9ugbc6u"/><path class="a1aa9h--o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doodle-jump" /></template>
<style>
.a1aa9h--o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.761 32.582c5.652-1.884 10.297-2.567 13.448-3.086s7.244-1.3 8.543-1.624m-23.648.714c1.767-.78 17.313-3.118 22.64-4.352m-19.62 12.051c.65-.617.423-.974 2.405-1.267s6.139-1.104 10.33-2.11s7.308-1.528 8.64-1.04m6.506-17.93c-.114 1.332.942 5.007 2.894 6.293M28.574 33.72l1.04 4.353a21 21 0 0 0 2.988-.488m-9.03-2.306c.054 1.632.403 3.056.716 4.515a3.4 3.4 0 0 0 1.85-.032m-7.86-3.022c.022 1.782.184 3.35.552 4.613c.975.21 1.657.099 2.24-.13m-7.86-3.768c.183 1.703.35 3.298.196 4.58c.93.23 1.951.19 2.5 0");
}

.f_4ku1ico {
  cx: 21.997px;
  cy: 15.842px;
  r: 0.75px;
  fill: currentColor;
}

.mf5roac8n {
  cx: 25.373px;
  cy: 15.383px;
  r: 0.75px;
  fill: currentColor;
}

.yz9ugbc6u {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M29.898 24.434c-.506-2.16-.092-3.192 1.63-4.364s5.605-1.378 9.746.43c2.541-1.441.632-5.576-1.221-7.775c-4.482 2.845-8.18 3.602-11.029 1.628c-3.601-5.643-8.053-9.108-13.93-8.47c-4.583.498-8.673 5.75-9.42 10.135c-.779 4.483 1.236 8.867 2.307 12.245c1.105 3.866 1.885 6.886 2.08 9.355c5.392-.098 15.753-3.443 21.503-4.808c.065-1.429-.342-3.4-1.665-8.375z");
}

</style>
