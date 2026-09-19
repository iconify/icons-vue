<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aw8cc5alt"/><path class="gwu91igie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:everydady-tasks" /></template>
<style>
.aw8cc5alt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.272 18.654A20 20 0 0 1 44 24h0a20 20 0 1 1-8.678-16.487");
}

.gwu91igie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.873 24.204l7.295 7.376l22.34-23.092");
}

</style>
