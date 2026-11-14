<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jij6jzbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-hall" /></template>
<style>
.jij6jzbts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 7.5l9.5-5l9.5 5Zm0 14V19h2v-2.5h15V19h2v2.5Zm4-14v9m5.5-9v9m5.5-9v9");
}

</style>
