<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ymbou6n6v"/><path class="hlc3d4z6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-alt-map-pin-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hlc3d4z6o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 21H7.5C-1 14 5 8 9 3c1.663 2.078 3.671 4.33 4.84 6.754M7.5 21C3 17.5 5 14.5 9 11a28 28 0 0 1 1.817 1.718M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

.ymbou6n6v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.368 19.992Q6.914 20.518 7.5 21a10.4 10.4 0 0 1-1.132-1.008M9 3c1.663 2.078 3.671 4.33 4.84 6.754a7 7 0 0 0-3.023 2.964Q9.947 11.818 9 11c-3.611 3.16-5.592 5.912-2.632 8.992C.087 13.917 4.417 8.617 8.115 4.091Q8.56 3.548 9 3m8 18c-1.574-1.051-2.999-3.053-3-5a3 3 0 1 1 6 0c-.001 1.947-1.426 3.949-3 5");
}

</style>
