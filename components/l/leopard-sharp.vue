<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bu__6tbem"/><path class="e_5hflj4h"/><path class="o-ptqvbln"/><path class="lr6id3byi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:leopard-sharp" /></template>
<style>
.bu__6tbem {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 9l-.25-3.75V3.538l1.4.862L9.5 6l1.28-.4h2.44l1.28.4l2.85-1.6l1.4-.862V5.25L18.5 9l1.5 1.875V14.5l1 1.25l-1.75.25c-1.25 3.25-4 5-7.25 5s-6-1.75-7.25-5L3 15.75l1-1.25v-3.625z");
}

.e_5hflj4h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 8.25h.01m2.99 0h.01m-7.01 5.5h.01m10.99 0h.01");
}

.lr6id3byi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 11.25h.01m5.49 0h.01");
}

.o-ptqvbln {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 14.25h2l-1 1Zm1 1v1.25h-1.25M12 15.25v1.25h1.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
