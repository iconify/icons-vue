<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="c2sj-bb0l"/><path class="odxiyyb_i"/><path class="yj-ptlb0d"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="gwhfoytcg"/><path class="w4_ysudzy"/><path class="v_f8cdb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-patch-duotone-bold" /></template>
<style>
.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c2sj-bb0l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7.5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.gwhfoytcg {
  d: path("M12 7.5v4");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.odxiyyb_i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 9.5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v_f8cdb5o {
  d: path("M10 14.5h4");
}

.w4_ysudzy {
  d: path("M10 9.5h4");
}

.yj-ptlb0d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 14.5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
