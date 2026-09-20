<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ptz0jvb3k"/><path class="gsz4k90ej"/><path class="s5-57zhtp"/><path class="h-ljjxb1p"/><path class="izmrq5b4m"/><path class="eeoxujb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keep-left-duotone-thin" /></template>
<style>
.eeoxujb4a {
  d: path("m14 11 5 -5");
}

.gsz4k90ej {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 10.5V6h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h-ljjxb1p {
  d: path("M12 22v-9L5 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izmrq5b4m {
  d: path("M5 10.5V6h4.5");
}

.ptz0jvb3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 22v-9L5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s5-57zhtp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 11 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
