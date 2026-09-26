<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s5mng-f5a"/><path class="cpg4t9x5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-sharp-duotone" /></template>
<style>
.cpg4t9x5k {
  d: path("M8 17C8 18.1046 7.1046 19 6 19C4.8954 19 4 18.1046 4 17C4 15.8954 4.8954 15 6 15C7.1046 15 8 15.8954 8 17ZM19 17C19 18.1046 18.1046 19 17 19C15.8954 19 15 18.1046 15 17C15 15.8954 15.8954 15 17 15C18.1046 15 19 15.8954 19 17Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s5mng-f5a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 17L1 13C1 12.8925 1.0173 12.7857 1.0513 12.6838L3.718 4.6838C3.8541 4.2754 4.2362 4 4.6667 4L13 4C13.2869 4 13.56 4.1232 13.7498 4.3384L18.5717 9.8031L22.3162 11.0513C22.7246 11.1874 23 11.5696 23 12L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17Z");
  stroke: none;
}

</style>
