<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr2pkzbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aircraft-spare-parts" /></template>
<style>
.pr2pkzbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 11.5l2.5 3h14l2.5-3M5 14.5v7h14v-7m-3.75-8.75l1.5.5v1.5l-1.5.5l-.5 1l.25 1.5l-1.5.75l-1-1h-1l-1 1l-1.5-.75l.25-1.5l-.5-1l-1.5-.5v-1.5l1.5-.5l.5-1L9 3.25l1.5-.75l1 1h1l1-1l1.5.75l-.25 1.5ZM12 7h.01");
}

</style>
