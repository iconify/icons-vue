<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jfrgku__i"/><path class="fm4oowb-p"/><path class="ezik40n3m"/><path class="fvt2-0orr"/><path class="u4sowhi7h"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cold-snap-duotone-regular" /></template>
<style>
.ezik40n3m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fm4oowb-p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fvt2-0orr {
  d: path("M12 4v8m-4 0 8 -8");
}

.jfrgku__i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v8m-4 0 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4sowhi7h {
  d: path("M4 16h16");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
