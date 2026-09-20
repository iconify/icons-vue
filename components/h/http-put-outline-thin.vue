<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="rjyodzkad"/><path class="a9txaac_h"/><path class="j4d2337wb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-put-outline-thin" /></template>
<style>
.a9txaac_h {
  d: path("M12 10.5V16");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4d2337wb {
  d: path("m9.5 13 2.5 -2.5 2.5 2.5");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.rjyodzkad {
  d: path("M9.5 7.5h5");
}

</style>
