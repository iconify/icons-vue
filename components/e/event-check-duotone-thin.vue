<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebovp7bpp"/><path class="ro9lombns"/><path class="v-jogvb5z"/><path class="l9-vpjbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-check-duotone-thin" /></template>
<style>
.ebovp7bpp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9-vpjbes {
  d: path("m13 14 2.5 2.5L20 12");
}

.ro9lombns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 14 2.5 2.5L20 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

</style>
