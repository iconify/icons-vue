<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kosxb-loy"/><path class="e0-y-kb0c"/><path class="ecv39gisi"/><path class="skbifdbcx"/><path class="hnix93blm"/><path class="gpzsx6dgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-power-duotone-regular" /></template>
<style>
.e0-y-kb0c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.68 12.82a4.5 4.5 0 1 1 -6.36 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ecv39gisi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gpzsx6dgy {
  d: path("M16.5 10v5");
}

.hnix93blm {
  d: path("M19.68 12.82a4.5 4.5 0 1 1 -6.36 0");
}

.kosxb-loy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
