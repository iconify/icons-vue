<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q7skbsd9f"/><path class="hmylfkbub"/><path class="vd6h3lb9s"/><path class="lwxj9tbjf"/><path class="y6l2c7b5j"/><path class="iulb4mb6k"/><path class="qltxbpdvm"/><path class="tr_jskylo"/><path class="z3it7clmt"/><path class="leemd3bqp"/><path class="h9fb_9biv"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:isbn-duotone-regular" /></template>
<style>
.h9fb_9biv {
  d: path("M20 5v12");
}

.hmylfkbub {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.leemd3bqp {
  d: path("M15 5v12");
}

.lwxj9tbjf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 5v12");
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

.q7skbsd9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qltxbpdvm {
  d: path("M4 5v12");
}

.tr_jskylo {
  d: path("M7 5v12");
}

.vd6h3lb9s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y6l2c7b5j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z3it7clmt {
  d: path("M11 5v12");
}

</style>
