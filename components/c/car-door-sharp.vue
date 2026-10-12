<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zx5kl9bnl"/><path class="gnyze-b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-door-sharp" /></template>
<style>
.gnyze-b2w {
  d: path("m7.44 9.77l2.62-2.79l.69-.73h8v4.25h-12zM14.5 14h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zx5kl9bnl {
  d: path("m4.09 9.51l3.82-4.27l1.34-1.49h12v17.5H2.75V11z");
}

</style>
