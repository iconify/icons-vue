<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gte6ws6am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:big-bang" /></template>
<style>
.gte6ws6am {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7 1.75l4.25 1.5M11.5 17l-.25 2.5m-3.5-5l-4 2.25M8 9.25l-2.25-1.5M12 7V2.5m4 6.75l2.25-1.5m-1 11.5h.01m-13.76-8h.01m12.24-7h.01");
}

</style>
