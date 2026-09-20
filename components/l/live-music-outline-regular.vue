<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pe4oq0b5e"/><path class="mp2qg-3hm"/><path class="acr8x6wbq"/><path class="jrneb7jzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:live-music-outline-regular" /></template>
<style>
.acr8x6wbq {
  d: path("M15 9c2 2 2 6 0 8");
}

.jrneb7jzh {
  d: path("M18 6c3 3.5 3 10.5 0 14");
}

.mp2qg-3hm {
  d: path("M12 17V5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pe4oq0b5e {
  d: path("M6 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
