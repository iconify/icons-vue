<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_oqy2n_y"/><path class="kozm7-q3y"/><path class="m33dzwbkd"/><path class="e77gki8ci"/><path class="n92b0ebji"/><path class="m7aa3ibix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hold-at-depot-duotone-regular" /></template>
<style>
.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.kozm7-q3y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m33dzwbkd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7aa3ibix {
  d: path("M14.5 11v6");
}

.n92b0ebji {
  d: path("M9.5 11v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_oqy2n_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
