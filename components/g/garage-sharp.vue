<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub90b-hce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:garage-sharp" /></template>
<style>
.ub90b-hce {
  fill: currentColor;
  d: path("M2 22V2h20v20zm6.288-8.287Q8 13.425 8 13t.288-.712T9 12t.713.288T10 13t-.288.713T9 14t-.712-.288m6 0Q14 13.426 14 13t.288-.712T15 12t.713.288T16 13t-.288.713T15 14t-.712-.288M5 11.1v7.4h2v-2h10v2h2v-7.4l-1.925-5.6H6.925zm2.65-1.6l.7-2h7.3l.7 2z");
}

</style>
