<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iuoa3jb-c"/><path class="mishqo88l"/><path class="afo552p2d"/><path class="c0qm6tbuu"/><path class="tamizsb5w"/><path class="l8unaacgj"/><path class="e3aed6d4j"/><path class="pfpu_3ppl"/><path class="wskxlyzso"/><path class="e69i7fcek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delay-duotone-bold" /></template>
<style>
.afo552p2d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c0qm6tbuu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e3aed6d4j {
  d: path("M14.11 7.47a5 5 0 1 1 -4.22 0");
}

.e69i7fcek {
  d: path("M17 12h5");
}

.iuoa3jb-c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l8unaacgj {
  d: path("M2 12h5");
}

.mishqo88l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.11 7.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pfpu_3ppl {
  d: path("M12 8v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tamizsb5w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wskxlyzso {
  d: path("M12 12h3");
}

</style>
