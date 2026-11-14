<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oxkxtbcvo"/><path class="cx3249bwo"/><path class="tgh-r3-nu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cosmos-flower" /></template>
<style>
.cx3249bwo {
  fill: currentColor;
  d: path("M12 9.5h.01");
}

.oxkxtbcvo {
  d: path("m15.25 8.25l3.5-.25l-1.25 1.5l1.25 1.5l-3.5-.25l2.5 2.5l-1.75.25l-.25 1.75l-2.5-2.5l.25 3.5L12 15l-1.5 1.25l.25-3.5l-2.5 2.5L8 13.5l-1.75-.25l2.5-2.5l-3.5.25L6.5 9.5L5.25 8l3.5.25l-2.5-2.5L8 5.5l.25-1.75l2.5 2.5l-.25-3.5L12 4l1.5-1.25l-.25 3.5l2.5-2.5L16 5.5l1.75.25ZM12 15v6.5");
}

.tgh-r3-nu {
  d: path("M12 20.5c-1.5-1.75-4-2-5.5-1c1.5 1.75 4 2.25 5.5 1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
