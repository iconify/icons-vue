<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j-mu-_4iu"/><path class="vq9gfjb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:first-aid-kit-plus-sharp" /></template>
<style>
.j-mu-_4iu {
  d: path("M7.5 8h11l.41 1.96l1.93 9.33l.41 1.96H2.75l.41-1.96l1.93-9.33L5.5 8zM9 8V6.25a3 3 0 0 1 6 0V8m-8.5 3h11");
}

.vq9gfjb-n {
  d: path("M10.75 13.75h2.5V15h1.25v2.5h-1.25v1.25h-2.5V17.5H9.5V15h1.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
