<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6n49udox"/><path class="pwcdu7b1o"/><path class="j6jqp97zs"/><path class="n_h_kpigg"/><path class="h2-2dgnfu"/><path class="sm02sv71h"/><path class="gtujb54ma"/><path class="g_k4zfu5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diff-duotone-thin" /></template>
<style>
.g_k4zfu5d {
  d: path("M14 15h6");
}

.g6n49udox {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gtujb54ma {
  d: path("M4 9h6");
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6jqp97zs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_h_kpigg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pwcdu7b1o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sm02sv71h {
  d: path("M7 6v6");
}

</style>
