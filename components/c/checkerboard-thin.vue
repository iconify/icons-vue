<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ddqi98epf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:checkerboard-thin" /></template>
<style>
.ddqi98epf {
  fill: currentColor;
  d: path("M208 36H48a12 12 0 0 0-12 12v160a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V48a12 12 0 0 0-12-12m-14.34 88L132 62.34V44h18.34L212 105.66V124ZM132 73.66L182.34 124H132ZM212 48v46.34L161.66 44H208a4 4 0 0 1 4 4M48 44h76v80H44V48a4 4 0 0 1 4-4m57.66 168L44 150.34V132h18.34L124 193.66V212ZM124 182.34L73.66 132H124ZM44 208v-46.34L94.34 212H48a4 4 0 0 1-4-4m164 4h-76v-80h80v76a4 4 0 0 1-4 4");
}

</style>
