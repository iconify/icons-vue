<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="f1wdbk8nb"/><path class="gu5b9ub8b"/><path class="ouw0zmbdc"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="d4s5t4bpo"/><path class="y4-ssjnrw"/><path class="j4if4rbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-duotone-regular" /></template>
<style>
.d4s5t4bpo {
  d: path("M8 12v8");
}

.f1wdbk8nb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gu5b9ub8b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j4if4rbfv {
  d: path("M18 14v6");
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

.ouw0zmbdc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.y4-ssjnrw {
  d: path("M13 8v12");
}

</style>
