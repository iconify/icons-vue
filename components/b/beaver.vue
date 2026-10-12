<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xpyg2nfru"/><rect class="dp43zobsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beaver" /></template>
<style>
.dp43zobsu {
  width: 13px;
  height: 3px;
  x: 5.5px;
  y: 18.25px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpyg2nfru {
  d: path("M12 3.5c1.1 0 2.1.22 2.9.62a1.6 1.6 0 1 1 2.15 1.89c.15.35.2.7.25 1.05c1.2.84 1.7 2.16 1.45 3.26c-.25 1.54-2 2.42-4.25 2.42h.5v1.51c0 .55-.45 1-1 1h-4c-.55 0-1-.45-1-1v-1.51h.5c-2.25 0-4-.88-4.25-2.42C5 9.22 5.5 7.9 6.7 7.06c.05-.35.1-.7.25-1.05A1.6 1.6 0 1 1 9.1 4.12c.8-.4 1.8-.62 2.9-.62M9.75 6.75zm4.5 0zm-3.25 3h2M12 12v3.25");
}

</style>
