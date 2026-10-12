<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u2bb4mebz"/><rect class="jyvtkwloz"/><rect class="dp9eambrw"/><path class="i8h6zo32s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hole-punch" /></template>
<style>
.dp9eambrw {
  width: 3px;
  height: 6px;
  x: 13.25px;
  y: 9.25px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8h6zo32s {
  d: path("m3.48 8.32l16.29-4.14q.73-.18.97.53l.27.83q.24.71-.49.89L4.73 10.32Q4 10.5 3.6 9.86l-.45-.72q-.4-.64.33-.82");
}

.jyvtkwloz {
  width: 3px;
  height: 4.25px;
  x: 5.25px;
  y: 11px;
  rx: 0.75px;
}

.u2bb4mebz {
  width: 18.5px;
  height: 5.5px;
  x: 2.75px;
  y: 15.25px;
  rx: 1.5px;
}

</style>
