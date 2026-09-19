<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pt0smgbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cyan" /></template>
<style>
.pt0smgbtl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.225 27.797v10.759M10.829 43.5l11.693-14.49L34.215 43.5m-.78-31.748a3.13 3.13 0 0 1-3.134 3.122h0a3.13 3.13 0 0 1-3.134-3.122h0a3.13 3.13 0 0 1 3.134-3.122h0a3.13 3.13 0 0 1 3.134 3.122m3.736-.439c-.088 1.6-.27 3.155-1.545 4.835L30.3 23.153l-5.324-7.005c-1.275-1.68-1.457-3.235-1.546-4.835c0-3.763 3.074-6.813 6.87-6.813s6.87 3.05 6.87 6.813z");
}

</style>
