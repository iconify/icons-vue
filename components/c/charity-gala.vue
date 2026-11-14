<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="el0644bgo"/><path class="y05rtvbxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-gala" /></template>
<style>
.el0644bgo {
  d: path("m5 2.75l5 1l-2.5 7.75l-3-.75Zm1 8.5L4.5 20m-2-.25l4 .5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y05rtvbxt {
  d: path("m12.5 2.75l-4.75.75l2 7.75l3-.25ZM11.25 11l.166 2.995m.2 3.595L11.75 20m-1.5.25l2.663-.444M17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
