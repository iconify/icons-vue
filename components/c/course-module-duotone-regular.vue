<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mp0o2kdwg"/><path class="ajq5z5bvz"/><path class="vib1b5bye"/><path class="ve1q15bsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:course-module-duotone-regular" /></template>
<style>
.ajq5z5bvz {
  d: path("M4 9h11v11H4Z");
}

.mp0o2kdwg {
  fill: currentColor;
  d: path("M4 9h11v11H4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ve1q15bsq {
  d: path("m15 9 5 -5v11l-5 5");
}

.vib1b5bye {
  d: path("m4 9 5 -5h11l-5 5");
}

</style>
