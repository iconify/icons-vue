<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nsejy_1id"/><path class="th16b8bro"/><path class="dvw6-ubkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hedgehog-sharp" /></template>
<style>
.dvw6-ubkd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16.25V19m7-2.75V19");
}

.nsejy_1id {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 16.25l-1.46-3.08l3.69-.14l-1.31-3.42l3.31 1.6l.44-3.65l2.2 2.94l2.08-3.04l.59 3.63l3.25-1.73l-1.14 3.51l2.142-2.181l1.708 2.561l1 2.25l-1 .75h-2Z");
}

.th16b8bro {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 14h.01m2.49 1.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
