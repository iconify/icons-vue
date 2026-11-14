<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zalvvmlho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dispute-case" /></template>
<style>
.zalvvmlho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.909 3.02l7.071 7.071l-3.889 3.889L9.02 6.909ZM12.5 10.5L4 19m6.5-2.25h11v3h-11Z");
}

</style>
