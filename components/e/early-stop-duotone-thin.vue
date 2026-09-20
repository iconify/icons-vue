<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bma-fibzo"/><path class="leef4tbvz"/><path class="gh1l41bbm"/><path class="t3rq50btb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:early-stop-duotone-thin" /></template>
<style>
.bma-fibzo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 5 6 6h4l3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gh1l41bbm {
  d: path("m3 5 6 6h4l3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.leef4tbvz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t3rq50btb {
  d: path("M19 4v16");
}

</style>
