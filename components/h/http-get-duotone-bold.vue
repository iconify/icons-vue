<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="rcft4vcdq"/><path class="wg8yy7bob"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="q8d90--8n"/><path class="bfi7-obrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-get-duotone-bold" /></template>
<style>
.bfi7-obrv {
  d: path("M9.5 11.5 12 14l2.5 -2.5");
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

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.q8d90--8n {
  d: path("M12 8.5V14");
}

.rcft4vcdq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8.5V14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wg8yy7bob {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 11.5 12 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
