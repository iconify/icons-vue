<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0l7vgbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chicane" /></template>
<style>
.i0l7vgbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5v-4c0-5 6-6 6-11v-4m3 19v-4c0-5 6-6 6-11v-4M9 21.5v-3m2-5.5l2-2m2-5.5v-3");
}

</style>
