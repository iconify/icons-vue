<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nj2fbya"/><path class="bg2ejdbaq"/><path class="b1ja9gnou"/><path class="z0kumyy5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:double-entry-outline-thin" /></template>
<style>
.b1ja9gnou {
  d: path("M5 10h4.5");
}

.bg2ejdbaq {
  d: path("M12 5v16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.z0kumyy5w {
  d: path("M14.5 14H19");
}

</style>
