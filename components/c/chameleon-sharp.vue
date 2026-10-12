<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i1hlkltym"/><path class="zssfew0xz"/><path class="use-rmbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chameleon-sharp" /></template>
<style>
.i1hlkltym {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5L5 9l.793-1.427L7.5 8C9 7 11 6.5 13 6.75c3 .4 5.25 2.75 5.25 5.75c0 1.75-1.25 3-3 3H3z");
}

.use-rmbfv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 11.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zssfew0xz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 13.75c1.75.5 2.75 2 2.5 3.75c-.25 1.5-1.75 2.25-3 1.75l-2.118-.847L17 17l1.5-1.25v1.75m-11-2l-1 4.25m6-4.25l1 4.25m-10.75 0h11.5");
}

</style>
