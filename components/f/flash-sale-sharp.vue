<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fo5nwek2p"/><path class="uw3jnusza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flash-sale-sharp" /></template>
<style>
.fo5nwek2p {
  d: path("m5.1 8.4l.094-1.643L6.84 6.75h10.32l1.646.007L18.9 8.4l.7 10.3l.051 2.551l-2.551-.001H6.9l-2.551.001L4.4 18.7Z");
}

.uw3jnusza {
  d: path("M8.75 9.75V6.5a3.25 3.25 0 0 1 6.5 0v3.25m-2.5 1l-2.5 4h3.5l-2.5 4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
