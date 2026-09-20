<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hpm6v1-ys"/><path class="j57oimz9k"/><path class="zv21m0g3f"/><path class="lb2q54bru"/><path class="fgef0hcge"/><path class="jkuojibnm"/><path class="v9qvd19wv"/><path class="wcigoab1j"/><path class="mtax_6bie"/><path class="t3rq50btb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:latency-p99-duotone-bold" /></template>
<style>
.fgef0hcge {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j57oimz9k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.lb2q54bru {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 16v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mtax_6bie {
  d: path("M13 16v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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

.zv21m0g3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
