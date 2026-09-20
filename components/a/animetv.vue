<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hspiruwre"/><path class="btmyyg2tr"/><path class="matbpcsha"/><path class="np-vi02kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:animetv" /></template>
<style>
.btmyyg2tr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 30.167H24a6.167 6.167 0 1 1 6.167-6.166zc0 6.812 5.522 12.333 12.333 12.333V24");
}

.hspiruwre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.293 39.372A18.5 18.5 0 0 1 24 42.5C13.783 42.5 5.5 34.217 5.5 24S13.783 5.5 24 5.5S42.5 13.783 42.5 24");
}

.matbpcsha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24c0-6.811 5.522-12.333 12.333-12.333S30.166 17.19 30.166 24");
}

.np-vi02kh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5c-6.811 0-12.333-5.522-12.333-12.333S17.189 17.834 24 17.834");
}

</style>
