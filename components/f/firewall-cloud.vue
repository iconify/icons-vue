<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-l7j4g7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firewall-cloud" /></template>
<style>
.x-l7j4g7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 18.5a4.5 4.5 0 0 1 0-9a6 6 0 0 1 11 0a4.5 4.5 0 0 1 0 9ZM5 14h14m-7-4.5V14m-3.5 0v4.5m7-4.5v4.5");
}

</style>
