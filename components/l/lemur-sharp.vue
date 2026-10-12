<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kfkpg7b0s"/><circle class="qcu4hfb6l"/><circle class="p2q4etbna"/><path class="j6-on0b5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lemur-sharp" /></template>
<style>
.j6-on0b5z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 10h.01m6.49 0h.01M12 18.5h.01");
}

.kfkpg7b0s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21h-1l-.35-1.05l-2.15-5.2l-4.25-1.275V9l-1.5-2.5c2-.75 3.75-.5 5 .5l2.083-1.25h4.334L16.25 7c1.25-1 3-1.25 5-.5L19.75 9v4.475L15.5 14.75l-2.15 5.2L13 21z");
}

.p2q4etbna {
  cx: 15.25px;
  cy: 10px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qcu4hfb6l {
  cx: 8.75px;
  cy: 10px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
