<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwk4n1tai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grizzly-screen" /></template>
<style>
.xwk4n1tai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.995 7.854l15.036 5.473M3.798 11.143l15.036 5.473M2.601 14.432l15.035 5.472M5.935 8.196l1.838-3.587l3.332-.384L12.77 6.96l-1.197 3.288Zm7.988 2.907l1.324-2.178l2.692-.084l1.366 2.093l-.684 1.88Z");
}

</style>
