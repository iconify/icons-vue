<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><circle class="zz413hbju"/><path class="skms4sbjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:card-clock-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.skms4sbjj {
  d: path("M12 6.75v1.5L13 9m-5 4.25h8M8 16h8m-8 2.75h5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zz413hbju {
  cx: 12px;
  cy: 8px;
  r: 2.75px;
}

</style>
