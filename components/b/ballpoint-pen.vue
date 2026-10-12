<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="t3at5yb7h"/><path class="jpi3fd3cp"/><path class="ul_okxbqo"/><path class="zhq--2b9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ballpoint-pen" /></template>
<style>
.jpi3fd3cp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.07 16.51l1.42 1.42q1.06 1.06 2.12 0l7.6-7.61q1.06-1.06 0-2.12L15.8 6.79q-1.06-1.06-2.12 0l-7.61 7.6q-1.06 1.06 0 2.12m1.42-3.53l3.53 3.53m4.42-7.95l-3.35 3.35");
}

.t3at5yb7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.15 7.14l.71.71q.53.53 1.06 0l.88-.89q.53-.53 0-1.06l-.7-.7q-.53-.53-1.06 0l-.89.88q-.53.53 0 1.06");
}

.ul_okxbqo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.41 19.84l2.97-1.35q.46-.21.11-.56l-1.42-1.42q-.35-.35-.56.11l-1.35 2.97q-.21.46.25.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhq--2b9z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.95 20.05h.01");
}

</style>
