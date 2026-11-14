<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6wdrsbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firewall" /></template>
<style>
.l6wdrsbkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 18.5H2.5v-16h17v4.6m-17 .65h15.1m-15.1 5.5h11.2M11 2.5v5.25m-4.25 0v5.5m8.5-5.5v4M11 13.25v5.25m7-6c.5 2 3.5 3 3.5 5.5a3.5 3.5 0 0 1-7 0c0-1.5.75-2.5 1.5-3c0 1 .5 1.5 1 1.75c0-1.5.25-3 1-4.25Z");
}

</style>
