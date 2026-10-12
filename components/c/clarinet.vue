<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p0izeebnv"/><path class="zx0fzjfgz"/><path class="q8fgkhbvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clarinet" /></template>
<style>
.p0izeebnv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6V3.75q0-1 1-1h1q1 0 1 1V6Z");
}

.q8fgkhbvv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01M12 13h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zx0fzjfgz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 6h2.5q.75 0 .75.75v9q0 .75.38 1.4l1.99 3.45q.38.65-.37.65H8q-.75 0-.37-.65l1.99-3.45q.38-.65.38-1.4v-9q0-.75.75-.75");
}

</style>
