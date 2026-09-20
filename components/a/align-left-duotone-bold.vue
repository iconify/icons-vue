<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="n45vxib8e"/><path class="bxojdxbnt"/><path class="xgrfb-bqu"/><path class="x22av82oi"/><path class="cn-9z7b7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-left-duotone-bold" /></template>
<style>
.bxojdxbnt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cn-9z7b7f {
  d: path("M3 18h15");
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n45vxib8e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x22av82oi {
  d: path("M3 12h11");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
