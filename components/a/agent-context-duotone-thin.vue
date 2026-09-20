<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="hdp7mqb1p"/><path class="mu77qebcm"/><path class="skbifdbcx"/><path class="qn5d-0b_j"/><path class="jkpgw6k5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-context-duotone-thin" /></template>
<style>
.ft030md1w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hdp7mqb1p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 12H12v9h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkpgw6k5z {
  d: path("M19.5 12H22v9h-2.5");
}

.mu77qebcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.5 12H22v9h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qn5d-0b_j {
  d: path("M14.5 12H12v9h2.5");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
