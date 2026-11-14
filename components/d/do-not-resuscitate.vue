<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8z8uabmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:do-not-resuscitate" /></template>
<style>
.p8z8uabmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.996 17.849q-.48.323-.996.651a45 45 0 0 1-1.513-1.004m-4.245-3.683C3.721 12.009 3 10.149 3 8c0-2.5 2-4.5 4.25-4.5c1.75 0 3 1 3.75 2.25c.75-1.25 2-2.25 3.75-2.25q.348 0 .686.062M19 7.986V8c0 1.808-.511 3.412-1.579 4.95M19.5 3.5l-16 16M19 14.75l-3.75 3.75H18l-1 3.25l4-4h-2.75Z");
}

</style>
