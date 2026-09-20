<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vztq54byw"/><path class="kic8axbqv"/><path class="acx2mjbnt"/><path class="ikiprn9sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blood-donation-duotone-regular" /></template>
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

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vztq54byw {
  fill: currentColor;
  d: path("m12 5 8 8a8 8 0 1 1 -16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
