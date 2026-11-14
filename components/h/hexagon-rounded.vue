<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0jrv1_lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hexagon-rounded" /></template>
<style>
.s0jrv1_lh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.138 5.744l2.349 4.069a4.38 4.38 0 0 1 0 4.375l-2.349 4.068a4.38 4.38 0 0 1-3.789 2.188H9.651a4.38 4.38 0 0 1-3.789-2.188l-2.349-4.068a4.38 4.38 0 0 1 0-4.375l2.349-4.069a4.38 4.38 0 0 1 3.789-2.188h4.698a4.38 4.38 0 0 1 3.789 2.188");
}

</style>
