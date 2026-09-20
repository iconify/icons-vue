<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2-2dgnfu"/><path class="sm02sv71h"/><path class="gtujb54ma"/><path class="g_k4zfu5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diff-outline-thin" /></template>
<style>
.g_k4zfu5d {
  d: path("M14 15h6");
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

.sm02sv71h {
  d: path("M7 6v6");
}

</style>
