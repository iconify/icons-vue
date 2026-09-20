<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="mnxytbb7g"/><path class="ab5v244hw"/><path class="wo3g0129h"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="li19mgbhm"/><path class="a-ogebbgz"/><path class="fl5-97bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:api-quota-duotone-thin" /></template>
<style>
.a-ogebbgz {
  d: path("M12 7v9");
}

.ab5v244hw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fl5-97bom {
  d: path("M15 12v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.li19mgbhm {
  d: path("M9 10v6");
}

.mnxytbb7g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wo3g0129h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
