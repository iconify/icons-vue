<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGF7MPLd7a)" class="qnt2bz84g"/><path class="c8v1d9b2d"/><path class="zww7vsbar"/><path fill="url(#SVGSmiTWc5g)" clip-rule="evenodd" class="o3w6dibkr"/><defs><linearGradient id="SVGF7MPLd7a" x1="18.099" x2="5.634" y1="5.901" y2="18.366" gradientUnits="userSpaceOnUse"><stop class="nty9n2b4g"/><stop offset="1" class="ococht1jo"/></linearGradient><linearGradient id="SVGSmiTWc5g" x1="21" x2="3.53" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="vfj76204k"/><stop offset="1" class="nrs3zc1la"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ejs" /></template>
<style>
.c8v1d9b2d {
  fill: var(--svg-color--ea3d72, #ea3d72);
  d: path("m6.75 14.91l2.77-2.765a.701.701 0 1 1-.996-.99l-2.34 2.335c.13.49.315.97.565 1.42m5.1-.425L9.09 17.25c.45.25.93.435 1.42.564l2.424-2.43l-.09.09a.703.703 0 0 1-.995-.99");
}

.ft5dv1b6b {
  fill: none;
}

.nrs3zc1la {
  stop-color: var(--svg-color--e54077, #e54077);
}

.nty9n2b4g {
  stop-color: var(--svg-color--8f3eda, #8f3eda);
}

.o3w6dibkr {
  fill-rule: evenodd;
  d: path("M12 20.5a8.5 8.5 0 1 0 0-17a8.5 8.5 0 0 0 0 17m0 .5a8.997 8.997 0 0 0 9-9a9 9 0 0 0-9-9a9 9 0 0 0 0 18");
}

.ococht1jo {
  stop-color: var(--svg-color--e73e73, #e73e73);
}

.qnt2bz84g {
  d: path("m16.064 7.93l-4.385 1.2l.425.43l-2.585 2.586a.701.701 0 1 1-.995-.99L13.49 6.19a6 6 0 1 0 4.32 4.32l-4.966 4.965a.702.702 0 0 1-.99-.995l2.585-2.585l.47.465z");
}

.vfj76204k {
  stop-color: var(--svg-color--864bd0, #864bd0);
}

.zww7vsbar {
  fill: var(--svg-color--730d2b, #730d2b);
  d: path("M12.174 14.16L9.09 17.25l.305.155l2.27-2.27a.7.7 0 0 1 .19-.65zm-5.885-.31l2.05-2.04a.71.71 0 0 1 .185-.655l-2.34 2.335l.105.364z");
}

</style>
