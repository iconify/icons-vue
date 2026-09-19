<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pamj-nbca"/><path class="u6kq8elkf"/><circle class="eu5aywbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:instabridge" /></template>
<style>
.eu5aywbnj {
  cx: 32.987px;
  cy: 29.014px;
  r: 1.134px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pamj-nbca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.592 26.396a9.98 9.98 0 0 0-8.92 1.948v.035m6.348 4.085a4 4 0 1 0 4 4h0a4 4 0 0 0-4-4m7.279-14.087a19.62 19.62 0 0 0-19.761 3.086M42.5 14.204c-10.731-8.89-26.268-8.89-37 0m23.6 11.401h7.778c.295 0 .534.24.534.534v5.749a.534.534 0 0 1-.534.534H29.1a.534.534 0 0 1-.534-.534v-5.749c0-.295.239-.534.534-.534");
}

.u6kq8elkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.062 25.605v-2.46a2.925 2.925 0 0 1 5.85 0");
}

</style>
