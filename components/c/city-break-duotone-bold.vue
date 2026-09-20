<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j555rthsv"/><path class="fbwe-c6ry"/><path class="asg4o-dea"/><path class="u9cgndnjv"/><path class="tp3wfdbxm"/><path class="n36352b2b"/><path class="j3g0obcgt"/><path class="m_ifpmwzr"/><path class="w-c31ggft"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:city-break-duotone-bold" /></template>
<style>
.asg4o-dea {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fbwe-c6ry {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 21V4h6v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j3g0obcgt {
  d: path("M13 21V4h6v17");
}

.j555rthsv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 21V8h6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m_ifpmwzr {
  d: path("M4 12h6");
}

.n36352b2b {
  d: path("M4 21V8h6v13");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tp3wfdbxm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u9cgndnjv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-c31ggft {
  d: path("M13 9h6");
}

</style>
