<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ma6u-bclm"/><path class="leunt80ih"/><path class="g1qd6i6pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:magicpin" /></template>
<style>
.g1qd6i6pd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.93 20.87c0 5.815-7.93 10.962-7.93 10.962s-7.93-5.147-7.93-10.961a7.93 7.93 0 1 1 15.86 0");
}

.leunt80ih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.72c6.71 0 12.15 5.44 12.15 12.15C36.15 29.78 24 37.667 24 37.667S11.85 29.78 11.85 20.871c0-6.71 5.44-12.15 12.15-12.15");
}

.ma6u-bclm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.37 20.87C40.37 32.874 24 43.5 24 43.5S7.63 32.873 7.63 20.87C7.63 11.83 14.958 4.5 24 4.5s16.37 7.33 16.37 16.37");
}

</style>
