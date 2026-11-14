<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8q10lbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anti-itch" /></template>
<style>
.k8q10lbtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5h7.5l2 2.75v3.5l-2 2.75H3M3 6v12m9.5-7.75h3v3.5h-3ZM18.25 8q1-1.25 2 0t1.25.5M18.25 12q1-1.25 2 0t1.25.5M18.25 16q1-1.25 2 0t1.25.5");
}

</style>
