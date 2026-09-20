<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="ovsyibbby"/><path class="dg_wneqtd"/><path class="k6nj2fbya"/><path class="cbvfl-_0s"/><path class="f0zlw3bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drilldown-duotone-regular" /></template>
<style>
.cbvfl-_0s {
  d: path("M6 9v4h15");
}

.dg_wneqtd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 15v4h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f0zlw3bmh {
  d: path("M10 15v4h11");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ovsyibbby {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 9v4h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
