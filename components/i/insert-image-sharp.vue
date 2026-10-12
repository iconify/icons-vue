<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mx0g23bpk"/><path class="qx7i5x3qf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insert-image-sharp" /></template>
<style>
.mx0g23bpk {
  d: path("M12.75 3.75h-9v16.5h16.5v-8.5M3.75 16.5L8 12.25l3.5 3.5l2-2l3.5 3.5");
}

.qx7i5x3qf {
  d: path("M17.75 2.75v6.5m-2.5-2.5l2.5 2.5l2.5-2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
