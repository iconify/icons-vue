<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htphvib2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-up" /></template>
<style>
.htphvib2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h7.5V7H4ZM7.75 7v2m6.351 5.5H2.5L4 9h16l.842 3.087M18.601 14.5h-3.7m-.801 7H2.5v-7h11.6m.8 0h3.8m2.8 5.2v1.8h-1.7M14 11.75h.01m2.99 0h.01M6.5 18h4m4 0l2.5 2.5l4.5-5");
}

</style>
