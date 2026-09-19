<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c3f-hsbol"/><path class="kmu5hfb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dropbox-passwords" /></template>
<style>
.c3f-hsbol {
  cx: 24px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kmu5hfb4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 17c-3.9 0-7 3.1-7 7s3.1 7 7 7v7.5c0 2.2-1.8 4-4 4h-29c-2.2 0-4-1.8-4-4V31c3.9 0 7-3.1 7-7s-3.1-7-7-7V9.5c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4zM24 17V5.5M24 31v11.5");
}

</style>
