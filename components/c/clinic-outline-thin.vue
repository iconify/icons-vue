<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fr20hdeft"/><path class="ptaeireto"/><path class="e8vupfb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clinic-outline-thin" /></template>
<style>
.e8vupfb9c {
  d: path("M9.5 14h5");
}

.fr20hdeft {
  d: path("M3 20v-8h5V7h8v5h5v8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ptaeireto {
  d: path("M12 11.5v5");
}

</style>
