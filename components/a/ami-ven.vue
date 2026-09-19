<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vd9bwtbuy"/><path class="ez1_f8bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ami-ven" /></template>
<style>
.ez1_f8bdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 12.291c-32.84 0-39 3.016-39 10.817c0 9.073 7.791 12.601 14.058 12.601c11.585 0 24.942-3.39 24.942-23.418");
}

.vd9bwtbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.713 29.925a7.5 7.5 0 0 1 0-10.607h0a7.5 7.5 0 0 1 10.607 0h0a7.5 7.5 0 0 1 0 10.607h0");
}

</style>
