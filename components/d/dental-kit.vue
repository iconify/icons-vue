<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxjga4pbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-kit" /></template>
<style>
.wxjga4pbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5h19V21h-19Zm2 0V8a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2.5m1.5 0l6.718-6.718m-5.304 1.061l2.829-2.828l2.121 2.121l-2.828 2.828Z");
}

</style>
