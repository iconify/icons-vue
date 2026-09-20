<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pga6n1bci"/><path class="ngkctb2wl"/><path class="wxgi9ty8e"/><path class="m-j5h280r"/><path class="dbfzjzb3n"/><path class="jkuojibnm"/><path class="v9qvd19wv"/><path class="wcigoab1j"/><path class="mtax_6bie"/><path class="t3rq50btb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:latency-p99-duotone-regular" /></template>
<style>
.dbfzjzb3n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.m-j5h280r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 16v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mtax_6bie {
  d: path("M13 16v4");
}

.ngkctb2wl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pga6n1bci {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t3rq50btb {
  d: path("M19 4v16");
}

.v9qvd19wv {
  d: path("M5 11v9");
}

.wcigoab1j {
  d: path("M9 14v6");
}

.wxgi9ty8e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
