<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zaxsh8bsw"/><path class="gahoblbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-square-dashed-duotone" /></template>
<style>
.gahoblbox {
  d: path("M20 9C21.1046 9 22 9.8954 22 11M22 15L22 16M22 20C22 21.1046 21.1046 22 20 22M16 22L15 22M11 22C9.8954 22 9 21.1046 9 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zaxsh8bsw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 9C17 13.4183 13.4183 17 9 17C4.5817 17 1 13.4183 1 9C1 4.5817 4.5817 1 9 1C13.4183 1 17 4.5817 17 9Z");
  stroke: none;
}

</style>
