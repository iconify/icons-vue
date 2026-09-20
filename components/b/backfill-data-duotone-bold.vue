<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="mfc2z2b-g"/><path class="c44js-bmo"/><path class="hf0dcmbwd"/><path class="jdh2e3b6a"/><path class="k6nj2fbya"/><path class="a6mnjib5x"/><path class="l8vricc3a"/><path class="t8troqb7m"/><path class="yngda3bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backfill-data-duotone-bold" /></template>
<style>
.a6mnjib5x {
  d: path("M3 10h4");
}

.c44js-bmo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hf0dcmbwd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 9 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jdh2e3b6a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.l8vricc3a {
  d: path("M17 10h4");
}

.mfc2z2b-g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t8troqb7m {
  d: path("m10 9 2 2 2 -2");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
