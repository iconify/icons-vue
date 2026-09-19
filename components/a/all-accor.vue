<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z11aybbvc"/><path class="rb3eiccla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:all-accor" /></template>
<style>
.rb3eiccla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.18 34.01s-2.026-1.753-2.026-3.935c0-3.126 3.598-5.131 2.36-8.552c3.774 2.477 4.007 8.009 4.007 8.009m1.713-17.21l11.324 23.356h-5.662s-6.32-13.33-7.377-15.747c-1.057-2.418-1.057-4.778 1.715-7.609m17.87 21.569V12.322h-4.246v21.57c0 .974.98 1.786 2.072 1.786h4.246c-1.092 0-2.072-.812-2.072-1.787m8.324 0V12.322h-4.246v21.57c0 .974.98 1.786 2.072 1.786H43.5c-1.092 0-2.072-.812-2.072-1.787");
}

.z11aybbvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 35.678c7.903-.236 9.437-11.265 16.573-10.44");
}

</style>
