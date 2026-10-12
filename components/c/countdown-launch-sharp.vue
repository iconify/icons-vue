<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l3-xedcsc"/><path class="xs_z1r2-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:countdown-launch-sharp" /></template>
<style>
.l3-xedcsc {
  d: path("M12 2.75A9.25 9.25 0 1 1 2.75 12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xs_z1r2-t {
  d: path("m12 6l2.25 1.875V14.5h-4.5V7.875zm-2.25 6.5L8.25 14v2l1.5-.75m4.5-2.75l1.5 1.5v2l-1.5-.75");
}

</style>
