<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qt9bodbdh"/><path class="gch2hkb1j"/><path class="px5-9pj7g"/><path class="khzxabbpm"/><path class="nwsr3kbjq"/><path class="orx4wjbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gloves-duotone-thin" /></template>
<style>
.gch2hkb1j {
  fill: currentColor;
  d: path("M15 21v-8a2.5 2.5 0 0 1 5 0v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.khzxabbpm {
  d: path("M15 21v-8a2.5 2.5 0 0 1 5 0v8Z");
}

.nwsr3kbjq {
  d: path("M6 17h6");
}

.orx4wjbhb {
  d: path("M15 18h5");
}

.px5-9pj7g {
  d: path("M6 21V10a3 3 0 0 1 6 0v11Z");
}

.qt9bodbdh {
  fill: currentColor;
  d: path("M6 21V10a3 3 0 0 1 6 0v11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
