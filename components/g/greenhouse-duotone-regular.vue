<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="evjfijbqj"/><path class="ckwdk7nmy"/><path class="r7xk8o29f"/><path class="pp1tvkbjf"/><path class="ioeb-3q9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:greenhouse-duotone-regular" /></template>
<style>
.ckwdk7nmy {
  d: path("M4 20v-8l8 -8 8 8v8Z");
}

.evjfijbqj {
  fill: currentColor;
  d: path("M4 20v-8l8 -8 8 8v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ioeb-3q9w {
  d: path("M16 13v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pp1tvkbjf {
  d: path("M8 13v7");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

</style>
