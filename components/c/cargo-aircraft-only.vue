<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hz51vnb5y"/><path class="l0__oybfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cargo-aircraft-only" /></template>
<style>
.hz51vnb5y {
  d: path("M3.5 4.5h17v15h-17Z");
}

.l0__oybfu {
  d: path("M12 7c.5 0 .75.5.75 1v2.5l3.25 2v1l-3.25-1V15L14 16v1l-2-.5l-2 .5v-1l1.25-1v-2.5L8 13.5v-1l3.25-2V8c0-.5.25-1 .75-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
