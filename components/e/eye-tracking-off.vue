<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnv05xbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-tracking-off" /></template>
<style>
.bnv05xbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8v-.6m3.973-3.9H8m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v.6m-3.973 3.9H16m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m8.337-.252C9.665 15.688 7.964 14.439 6.5 12q.3-.501.615-.935m5.08-2.812c2.157.071 3.849 1.32 5.305 3.747a13 13 0 0 1-.596.909M3.5 3.5l17 17");
}

</style>
