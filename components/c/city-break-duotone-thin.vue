<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq37i9b2h"/><path class="y8-35jqtf"/><path class="g5ovy6bxc"/><path class="ux3u_2gta"/><path class="hppiisbif"/><path class="n36352b2b"/><path class="j3g0obcgt"/><path class="m_ifpmwzr"/><path class="w-c31ggft"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:city-break-duotone-thin" /></template>
<style>
.g5ovy6bxc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hppiisbif {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j3g0obcgt {
  d: path("M13 21V4h6v17");
}

.m_ifpmwzr {
  d: path("M4 12h6");
}

.n36352b2b {
  d: path("M4 21V8h6v13");
}

.oq37i9b2h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21V8h6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.ux3u_2gta {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-c31ggft {
  d: path("M13 9h6");
}

.y8-35jqtf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 21V4h6v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
