<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ixstlqbmu"/><path class="xd679jbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:facade-sharp" /></template>
<style>
.ixstlqbmu {
  d: path("M2.75 20.75V9l.35-.36l1.95-2.03l.35-.36l.34.36l1.92 2.03L8 9V5.5h1.5V4h1.25V2.75h2.5V4h1.25v1.5H16V9l.34-.36l1.92-2.03l.34-.36l.35.36l1.95 2.03l.35.36v12.25H2.75zM5.4 12v2m0 2.5v2M18.6 12v2m0 2.5v2M12 7.75v1.5m-1.5 3.25h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xd679jbyp {
  d: path("M10.75 21.25V16.5h2.5v4.75");
}

</style>
