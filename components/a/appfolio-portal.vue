<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvfjoxrhm"/><circle class="m--thhb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:appfolio-portal" /></template>
<style>
.dvfjoxrhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.322 43.5l-16.494-2.519V7.912L29.322 4.5zm0-35.912h5.85v33.8");
}

.m--thhb8j {
  cx: 25.584px;
  cy: 26.173px;
  r: 1.503px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
