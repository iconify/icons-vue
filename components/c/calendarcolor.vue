<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c5c-1ft2b"/><path class="f523s-4dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendarcolor" /></template>
<style>
.c5c-1ft2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.38a13 13 0 0 0-13 13v0a12.93 12.93 0 0 1 13 0a12.93 12.93 0 0 1 13 0a13 13 0 0 0-13-13M11 18.39a13 13 0 1 0 13 22.48a13 13 0 0 1-6.5-11.23v0A13 13 0 0 1 11 18.39m26 0a13 13 0 0 1-6.5 11.24h0A13 13 0 0 1 24 40.86A13 13 0 1 0 37 18.4Z");
}

.f523s-4dl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.39a13 13 0 0 0-6.49 11.24a12.93 12.93 0 0 0 13 0A13 13 0 0 0 24 18.39");
}

</style>
