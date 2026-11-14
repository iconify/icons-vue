<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="egcfdmbbe"/><path class="i7-du0bfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:company-values" /></template>
<style>
.egcfdmbbe {
  d: path("m12 3l2 4.25L17 7l-.25 3L21 12l-4.25 2l.25 3l-3-.25L12 21l-2-4.25L7 17l.25-3L3 12l4.25-2L7 7l3 .25Z");
}

.i7-du0bfq {
  d: path("M12 15c-1.75-1.25-2.5-2.25-2.5-3.25S10.25 10 11 10c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c.75 0 1.5.75 1.5 1.75s-.75 2-2.5 3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
