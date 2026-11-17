<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2ternbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-wifi-corner-fill" /></template>
<style>
.u2ternbeg {
  fill: currentColor;
  d: path("M17.714 9H10a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9m-5.339 5.219A7.4 7.4 0 0 1 17 12.597a7.38 7.38 0 0 1 4.625 1.622a1 1 0 0 1-1.25 1.562a5.4 5.4 0 0 0-1.609-.888A5.4 5.4 0 0 0 17 14.597a5.4 5.4 0 0 0-3.375 1.184a1 1 0 0 1-1.25-1.562m1.918 3.074A3.82 3.82 0 0 1 17 16.172a3.82 3.82 0 0 1 2.707 1.121a.999.999 0 1 1-1.414 1.414A1.82 1.82 0 0 0 17 18.172a1.82 1.82 0 0 0-1.293.535a1.002 1.002 0 0 1-1.414-1.414M17 20h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
