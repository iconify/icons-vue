<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z2-5575fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ltecleaner" /></template>
<style>
.z2-5575fa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.76 22.8V15a2 2 0 0 0-2-2h-9.82V5.46a1 1 0 0 0-1-1H24a3.93 3.93 0 0 0-3.94 3.94v4.64h-9.85a2 2 0 0 0-2 2v7.76Zm-31.52 0v19.7a1 1 0 0 0 1 1h1.64a8.08 8.08 0 0 0 7.88-7.88v6.9a1 1 0 0 0 1 1h1.63a7.88 7.88 0 0 0 7.88-7.88v6.9a1 1 0 0 0 1 1h1.65a7.88 7.88 0 0 0 7.88-7.88V22.8Zm10.51 12.8V22.8m10.5 12.8V22.8");
}

</style>
