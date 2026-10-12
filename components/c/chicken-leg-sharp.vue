<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o6nkbhpbh"/><circle class="mq6912bci"/><circle class="pklpjen4v"/><path class="yo7_9ybfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chicken-leg-sharp" /></template>
<style>
.mq6912bci {
  cx: 4.75px;
  cy: 17.25px;
  r: 1.5px;
}

.o6nkbhpbh {
  d: path("M9 15.25c-.75-1.75-1.25-3.75-1.25-6a6.25 6.25 0 0 1 12.5 0c0 3.5-2.75 6.25-6.25 6.25c-1.75 0-3.25-.25-5-.25Zm0 0L6.25 18");
}

.pklpjen4v {
  cx: 6.75px;
  cy: 19.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yo7_9ybfj {
  d: path("M11.25 8.5V5.75H14");
}

</style>
