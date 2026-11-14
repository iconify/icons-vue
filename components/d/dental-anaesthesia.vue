<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihz2mthly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-anaesthesia" /></template>
<style>
.ihz2mthly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 13.25c-1-1-3.5-1.25-3.5 1.5c0 1.75.75 2.5 1 3.75l.75 2.25h.75l1-2.5l1 2.5h.75L10 18.5c.25-1.25 1-2 1-3.75c0-2.75-2.5-2.5-3.5-1.5Zm4.434-3.659l5.657-5.657l2.475 2.475l-5.657 5.657ZM18.75 5.25L21 3m-8 8l-2.25 2.25");
}

</style>
