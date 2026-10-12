<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="n6ud9o3ma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:card-spade-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.n6ud9o3ma {
  d: path("M12 6.75C10.5 9 7.5 10.5 7.5 13.25a2.5 2.5 0 0 0 4.1 1.9l-.6 2.1h2l-.6-2.1a2.5 2.5 0 0 0 4.1-1.9c0-2.75-3-4.25-4.5-6.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
