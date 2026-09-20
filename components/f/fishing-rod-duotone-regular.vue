<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u-6h9nqio"/><path class="mv9_3430k"/><path class="x5i0m055t"/><path class="zg5pq5bpo"/><path class="emvotkb4z"/><path class="veo4_yb-t"/><path class="wqwx994ue"/><path class="zqnyy8bad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fishing-rod-duotone-regular" /></template>
<style>
.emvotkb4z {
  d: path("M4 20 20 4");
}

.mv9_3430k {
  fill: currentColor;
  d: path("M13 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.u-6h9nqio {
  fill: currentColor;
  d: path("M6 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.veo4_yb-t {
  d: path("M6 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.wqwx994ue {
  d: path("M14 10v10");
}

.x5i0m055t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zg5pq5bpo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zqnyy8bad {
  d: path("M13 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
