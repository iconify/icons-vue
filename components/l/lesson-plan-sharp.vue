<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="mbfl6r2xl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lesson-plan-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.mbfl6r2xl {
  d: path("M11.5 2.75h4v6.5l-2-1.5l-2 1.5Zm-3.25 10h7.5m-7.5 3.75h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
