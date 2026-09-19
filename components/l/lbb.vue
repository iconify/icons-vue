<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7mw2xq6j"/><path class="hw5ugub2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lbb" /></template>
<style>
.f7mw2xq6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.967 37.048l8.966 6.029c1.534 1.032 3.232.058 3.232-1.673V6.66a2.16 2.16 0 0 0-2.16-2.16h-24a2.16 2.16 0 0 0-2.17 2.15v34.755c0 1.73 1.699 2.704 3.234 1.673l8.965-6.03c1.34-.9 2.594-.9 3.934 0z");
}

.hw5ugub2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.165 14.379L18.643 29.566c-.976.759-2.772.8-3.713 0l-5.095-4.33");
}

</style>
