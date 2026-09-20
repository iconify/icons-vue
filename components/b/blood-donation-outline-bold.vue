<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kic8axbqv"/><path class="acx2mjbnt"/><path class="ikiprn9sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blood-donation-outline-bold" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.ikiprn9sq {
  d: path("M9 14h6");
}

.kic8axbqv {
  d: path("m12 5 8 8a8 8 0 1 1 -16 0Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
