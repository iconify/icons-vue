<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="shz5qfbcl"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-front-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shz5qfbcl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M20.6364 9.9908C21.5033 10.7505 22.0003 11.8473 22 13L22 17.7574L13.2426 9L17.5598 9L16.3613 6.2104C16.0457 5.476 15.3232 5 14.5238 5L9.4762 5C9.4023 5 9.3284 5.0041 9.2549 5.0122L7.6724 3.4298C8.2316 3.147 8.8495 2.9998 9.4762 3L14.5238 3C16.1226 3 17.5678 3.952 18.1989 5.421L19.3069 8L20.5 8C21.0523 8 21.5 8.4477 21.5 9.0001C21.5 9.4997 21.1313 9.9226 20.6364 9.9908ZM4.6931 8L5.6869 5.6869L7.2095 7.2096L20.5715 20.5716C20.1081 20.8522 19.5767 21.0006 19.035 21.0006C17.8052 21.0006 16.7029 20.2416 16.2642 19.0927L16.1715 19L7.7694 19C7.3578 20.1974 6.2314 21.0013 4.9652 21.0013C3.327 21.0013 1.9992 19.6728 2 18.0346L2 13C1.9997 11.8473 2.4967 10.7505 3.3636 9.9908C2.8687 9.9226 2.5 9.4997 2.5 9.0001C2.5 8.4477 2.9477 8 3.5 8L4.6931 8ZM9 13.5C9 12.9477 8.5523 12.5 8 12.5C7.4477 12.5 7 12.9477 7 13.5L7 14.5C7 15.0523 7.4477 15.5 8 15.5C8.5523 15.5 9 15.0523 9 14.5L9 13.5Z");
  stroke: none;
}

</style>
