<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oq2nkbb8e"/><path class="arnjgwc1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bifold-door" /></template>
<style>
.arnjgwc1g {
  d: path("m6.5 7l2.75 1.5L12 7l2.75 1.5L17.5 7v10.5L14.75 19L12 17.5L9.25 19L6.5 17.5Zm2.75 1.5V19M12 7v10.5m2.75-9V19");
}

.oq2nkbb8e {
  d: path("M3 20.5v-17h18v17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
