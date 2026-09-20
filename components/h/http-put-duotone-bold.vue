<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="u4bivyvge"/><path class="za1ermbcy"/><path class="ob_gyjbjx"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="rjyodzkad"/><path class="a9txaac_h"/><path class="j4d2337wb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-put-duotone-bold" /></template>
<style>
.a9txaac_h {
  d: path("M12 10.5V16");
}

.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j4d2337wb {
  d: path("m9.5 13 2.5 -2.5 2.5 2.5");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.ob_gyjbjx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 13 2.5 -2.5 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rjyodzkad {
  d: path("M9.5 7.5h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u4bivyvge {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 7.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.za1ermbcy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10.5V16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
