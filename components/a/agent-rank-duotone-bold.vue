<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xmsxhfbtg"/><path class="e5c_ubczi"/><path class="uf-4xz-7y"/><path class="ps-_1ne9q"/><path class="s_yfbmb1g"/><path class="krpni0u_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-rank-duotone-bold" /></template>
<style>
.e5c_ubczi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 17.5 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.krpni0u_o {
  d: path("m7 22 5 -5 5 5");
}

.ps-_1ne9q {
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
}

.s_yfbmb1g {
  d: path("m7 17.5 5 -5 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uf-4xz-7y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 22 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xmsxhfbtg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
