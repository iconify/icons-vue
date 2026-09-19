<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s06qd4byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:l-speed" /></template>
<style>
.s06qd4byw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.79 12.72l21.24 29.06l17.76-12.99l-4.87-6.66l-11.1 8.12l-16.37-22.4Z");
}

</style>
