<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ui9rgnwwc"/><path class="y9toh5vyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incident-response" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ui9rgnwwc {
  width: 18.5px;
  height: 14px;
  x: 2.75px;
  y: 7px;
  rx: 2.25px;
}

.y9toh5vyj {
  d: path("M8.75 7V5.25a1.5 1.5 0 0 1 1.5-1.5h3.5a1.5 1.5 0 0 1 1.5 1.5V7M12 9.25h2.25q.5 0 .29.45l-1.08 2.35q-.21.45.29.45H15q.5 0 .2.4l-4.4 5.95q-.3.4-.3-.1v-3.5q0-.5-.5-.5H8.75q-.5 0-.25-.43l2.75-4.64q.25-.43.75-.43");
}

</style>
