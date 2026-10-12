<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ndoen1bbt"/><path class="bydqrccea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:excavator-sharp" /></template>
<style>
.bydqrccea {
  d: path("M17.5 10.25h3.75v4.5H17.5Z");
}

.ndoen1bbt {
  d: path("M2.75 16.75h12.5v4.5H2.75zM5.5 19h7m-8.75-2.25v-8.5h5.1l.867-.001l.433.751l2.6 4.5v3.25Zm0 0h9M6 11.25h3m3.75 1.5l3.75-7.5l3.75 5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
