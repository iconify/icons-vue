<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vahkufbuu"/><circle class="qcu4hfb6l"/><circle class="p2q4etbna"/><path class="j6-on0b5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lemur" /></template>
<style>
.j6-on0b5z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 10h.01m6.49 0h.01M12 18.5h.01");
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

.vahkufbuu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21c-.65 0-1.15-.45-1.35-1.05l-2.15-5.2C6 14 4.25 11.5 4.25 9l-1.5-2.5c2-.75 3.75-.5 5 .5C9 6.25 10.5 5.75 12 5.75s3 .5 4.25 1.25c1.25-1 3-1.25 5-.5L19.75 9c0 2.5-1.75 5-4.25 5.75l-2.15 5.2c-.2.6-.7 1.05-1.35 1.05");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
