<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nb_bhac3g"/><path class="g-4ao_sjh"/><path class="f7cjbzb4e"/><path class="dur27hb6c"/><path class="ozjd7j6vk"/><path class="f1a4nwu-v"/><path class="f2_a4gbcx"/><path class="s13m_784z"/><path class="he2cqebcu"/><path class="n96__jb1n"/><path class="o24qh25eq"/><path class="ov2ejkbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bm25-duotone-thin" /></template>
<style>
.dur27hb6c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f1a4nwu-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f2_a4gbcx {
  d: path("M2 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.f7cjbzb4e {
  fill: currentColor;
  d: path("M2 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g-4ao_sjh {
  fill: currentColor;
  d: path("M2 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.he2cqebcu {
  d: path("M2 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n96__jb1n {
  d: path("M6 12h11");
}

.nb_bhac3g {
  fill: currentColor;
  d: path("M2 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o24qh25eq {
  d: path("M2 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ov2ejkbhi {
  d: path("M6 17h7");
}

.ozjd7j6vk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s13m_784z {
  d: path("M6 7h15");
}

</style>
