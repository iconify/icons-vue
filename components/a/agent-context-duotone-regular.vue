<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kosxb-loy"/><path class="rzq22qepf"/><path class="gp9g24ber"/><path class="skbifdbcx"/><path class="qn5d-0b_j"/><path class="jkpgw6k5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-context-duotone-regular" /></template>
<style>
.gp9g24ber {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.5 12H22v9h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkpgw6k5z {
  d: path("M19.5 12H22v9h-2.5");
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

.qn5d-0b_j {
  d: path("M14.5 12H12v9h2.5");
}

.rzq22qepf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 12H12v9h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
