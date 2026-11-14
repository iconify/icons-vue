<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1bb183va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cross-post" /></template>
<style>
.x1bb183va {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5h7v9h-7Zm9.5 3l3-3m-2.75 0H15v2.75m-3 3.25l3 3m-2.75 0H15v-2.75M17.5 3.5h4v4h-4Zm0 13h4v4h-4Z");
}

</style>
