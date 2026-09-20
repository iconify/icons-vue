<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q6ohrfbvx"/><path class="c05oxkx8t"/><path class="ciyewebuj"/><path class="npc55tvzf"/><path class="xek3lp78w"/><path class="z5jtjknvm"/><path class="nooweob_o"/><path class="u9z5qccfn"/><path class="qnebkmpov"/><path class="zbj6wacas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-warm-duotone-bold" /></template>
<style>
.c05oxkx8t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ciyewebuj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nooweob_o {
  d: path("M3 10h12");
}

.npc55tvzf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 8 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q6ohrfbvx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnebkmpov {
  d: path("m18 8 2 -2 -2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u9z5qccfn {
  d: path("M3 15h12");
}

.xek3lp78w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 16 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z5jtjknvm {
  d: path("M3 5h12");
}

.zbj6wacas {
  d: path("m18 16 2 -2 -2 -2");
}

</style>
