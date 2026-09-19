<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dydm1yddd"/><path class="xugblft2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beptt" /></template>
<style>
.dydm1yddd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.25 21.214c3.158 0 5.468-2.494 5.468-5.571s-2.31-5.572-5.468-5.572h-5.967v11.143zm-.5 16.715c-3.158 0-5.467-2.494-5.467-5.571s2.31-5.572 5.467-5.572h5.968V37.93z");
}

.xugblft2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.435 43.5H24c-6.315 0-11.435-3.989-11.435-10.143V4.5H24c6.315 0 11.435 3.989 11.435 10.143z");
}

</style>
