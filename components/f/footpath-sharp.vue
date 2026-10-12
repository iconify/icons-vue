<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gsiuok5ol"/><circle class="zanv7q--q"/><path class="b7l4-ybbq"/><circle class="f-7dtmabf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:footpath-sharp" /></template>
<style>
.b7l4-ybbq {
  d: path("M14.25 6.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0Z");
}

.f-7dtmabf {
  cx: 17px;
  cy: 14.75px;
  r: 1.5px;
}

.gsiuok5ol {
  d: path("M4.25 11.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zanv7q--q {
  cx: 7px;
  cy: 19.75px;
  r: 1.5px;
}

</style>
