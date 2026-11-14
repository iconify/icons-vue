<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eql2-2bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:estuary" /></template>
<style>
.eql2-2bna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5V8L3 16M14.5 2.5V8l6.5 8M8.5 16l3.5-5l3.5 5M12 11v5m-9.5 3.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
