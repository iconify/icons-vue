<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="khas4pelr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dancerail3" /></template>
<style>
.khas4pelr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.6 27.7h3.7v3.7h-3.7zm-5.55 0h3.7v3.7h-3.7zm-5.55 0h3.7v3.7H5.5zm0-5.55h3.7v3.7H5.5zM22.15 5.5l3.7 3.7h-3.7zm5.55 11.1h3.7v3.7h-3.7zm5.55 0h3.7v3.7h-3.7zm-11.1 5.55h3.7v3.7h-3.7zm0 5.55h3.7v3.7h-3.7zm5.55 0h3.7v3.7h-3.7zm5.55 0h3.7v3.7h-3.7zm5.55 11.1h3.7v3.7h-3.7zm-16.65-5.55h3.7v3.7h-3.7zm0 5.55h3.7v3.7h-3.7zm16.65-5.55h3.7v3.7h-3.7zM5.5 16.6h3.7v3.7H5.5zm16.65-5.55h3.7v3.7h-3.7zm0 5.55h3.7v3.7h-3.7zM5.5 5.5h3.7v3.7H5.5zm0 5.55h3.7v3.7H5.5zm33.3 5.55l3.7 3.7h-3.7zm0 5.55h3.7v3.7h-3.7zM11.05 5.5h3.7v3.7h-3.7zm5.55 0h3.7v3.7h-3.7z");
}

</style>
