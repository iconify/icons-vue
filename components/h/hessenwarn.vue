<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sg_15459c"/><path class="ndgcv7bey"/><path class="hl828mbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hessenwarn" /></template>
<style>
.hl828mbfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.5c0-20.435 16.565-37 37-37");
}

.ndgcv7bey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.647 42.498c0-15.382 12.47-27.851 27.851-27.851");
}

.sg_15459c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.782 42.495a9.71 9.71 0 0 1 9.713-9.713v9.713zm-9.097-.002c0-10.387 8.42-18.808 18.808-18.808");
}

</style>
