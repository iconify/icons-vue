<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="yc90cabse"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="pk4lohtdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:availability-metric-duotone-regular" /></template>
<style>
.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pk4lohtdt {
  d: path("M7 7h5l2 2 2 -2h3");
}

.r3faxubne {
  d: path("M4 4v16");
}

.yc90cabse {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 7h5l2 2 2 -2h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
