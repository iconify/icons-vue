<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjd6lfpmr"/><path class="cjr_sf4wu"/><path class="drztn1bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librephotosmobile" /></template>
<style>
.cjr_sf4wu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.864 43.142l14.25-14.25a1.22 1.22 0 0 0 0-1.728h0l-14.25-14.25a1.22 1.22 0 0 0-1.728 0h0l-14.25 14.25a1.22 1.22 0 0 0 0 1.728h0l14.25 14.25a1.22 1.22 0 0 0 1.728 0");
}

.drztn1bgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.864 35.086l14.25-14.25a1.22 1.22 0 0 0 0-1.728h0l-14.25-14.25a1.22 1.22 0 0 0-1.728 0h0l-14.25 14.25a1.22 1.22 0 0 0 0 1.728h0l14.25 14.25a1.22 1.22 0 0 0 1.728 0");
}

.mjd6lfpmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.864 39.114l14.25-14.25a1.22 1.22 0 0 0 0-1.728h0l-14.25-14.25a1.22 1.22 0 0 0-1.728 0h0l-14.25 14.25a1.22 1.22 0 0 0 0 1.728h0l14.25 14.25a1.22 1.22 0 0 0 1.728 0");
}

</style>
