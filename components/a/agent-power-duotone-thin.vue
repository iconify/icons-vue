<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="qok4og0tb"/><path class="jct8clbxu"/><path class="skbifdbcx"/><path class="hnix93blm"/><path class="gpzsx6dgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-power-duotone-thin" /></template>
<style>
.ft030md1w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gpzsx6dgy {
  d: path("M16.5 10v5");
}

.hnix93blm {
  d: path("M19.68 12.82a4.5 4.5 0 1 1 -6.36 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jct8clbxu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qok4og0tb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.68 12.82a4.5 4.5 0 1 1 -6.36 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
