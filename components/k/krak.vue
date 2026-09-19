<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ympd9nbzq"/><path class="letwobbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krak" /></template>
<style>
.letwobbab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 39.701V26.8c0-10.218-8.283-18.5-18.5-18.5S5.5 16.58 5.5 26.799V39.7");
}

.ympd9nbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.62 39.701V26.8a6.38 6.38 0 1 1 12.76 0v12.9");
}

</style>
