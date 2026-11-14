<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ltkz_s1dv"/><path class="nbpaubcpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cockpit-weather-radar" /></template>
<style>
.ltkz_s1dv {
  d: path("M12.8 16.5H2.5v-13h19v10.9M12 16.5v1.3m-4 2.7h4");
}

.nbpaubcpp {
  d: path("M12 13.5L8 7.75a7 7 0 0 1 8 0Zm4.5 7.5H20a2 2 0 0 0 0-4a2.5 2.5 0 0 0-4.5 1a1.6 1.6 0 0 0 1 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
