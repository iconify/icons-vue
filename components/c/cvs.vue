<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mtpr6f5tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cvs" /></template>
<style>
.mtpr6f5tf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.139 15.225l-5.8-5.8a4.65 4.65 0 0 0-6.574 0L24 15.19l-5.765-5.765a4.65 4.65 0 0 0-6.573 0l-5.8 5.8a4.65 4.65 0 0 0 0 6.573l5.765 5.765L24 39.937l18.139-18.139a4.65 4.65 0 0 0 0-6.573");
}

</style>
