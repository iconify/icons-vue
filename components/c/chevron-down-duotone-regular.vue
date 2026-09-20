<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oxegj3-ei"/><path class="u54ztzb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-down-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oxegj3-ei {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 9 7 7 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u54ztzb9f {
  d: path("m5 9 7 7 7 -7");
}

</style>
