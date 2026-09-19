<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shdxazymr"/><path class="b2az7l9-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emkan" /></template>
<style>
.b2az7l9-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.62 21.638s.043-5.874 0-8.377c-.128-7.349 12.593-8.692 12.93 0c.126 3.255 0 10.428 0 10.428");
}

.shdxazymr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.405 26.1s6.252-.004 9.873 0c9.56.012 8.402 14.563-.186 14.646c-4.417.043-15.666 0-15.666 0m3.43-19.05s-9.1.007-12.514 0c-8.067-.016-8.64 13.532-.556 13.534H20.89");
}

</style>
