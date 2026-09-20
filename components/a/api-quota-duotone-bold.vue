<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="jd6xiqjbd"/><path class="u91se6bfv"/><path class="c27d3fbmh"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="li19mgbhm"/><path class="a-ogebbgz"/><path class="fl5-97bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:api-quota-duotone-bold" /></template>
<style>
.a-ogebbgz {
  d: path("M12 7v9");
}

.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c27d3fbmh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.fl5-97bom {
  d: path("M15 12v4");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jd6xiqjbd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.li19mgbhm {
  d: path("M9 10v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u91se6bfv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
