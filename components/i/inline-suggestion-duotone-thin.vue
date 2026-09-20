<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="qu01ihbhh"/><path class="on65-ubqx"/><path class="z2-ywbb3c"/><path class="hgolthvua"/><path class="xgrfb-bqu"/><path class="pesxdybze"/><path class="etqzyebuj"/><path class="y7_y8yq8z"/><path class="tb33trnmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inline-suggestion-duotone-thin" /></template>
<style>
.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.etqzyebuj {
  d: path("M13 12h2.5");
}

.hgolthvua {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.on65-ubqx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pesxdybze {
  d: path("M3 12h7");
}

.qu01ihbhh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tb33trnmj {
  d: path("M3 18h5");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.y7_y8yq8z {
  d: path("M18.5 12H21");
}

.z2-ywbb3c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 12H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
