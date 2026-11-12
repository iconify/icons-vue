<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ha7ctcc-i"/><path class="w74-afypo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightbulb-minimalistic-line-duotone" /></template>
<style>
.ha7ctcc-i {
  d: path("M10 19.5H14M10.6667 22H13.3333");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w74-afypo {
  d: path("M7.41058 13.6805C5.86939 12.2187 5.00875 10.2984 5.00007 8.30193L5 8.21807C5 4.8069 8.13401 2 12 2C15.866 2 19 4.8069 19 8.21807L18.9999 8.30193C18.9912 10.2984 18.1306 12.2187 16.5894 13.6805L15.4854 14.7196C15.1756 15.0112 15 15.4177 15 15.843C15 16.482 14.482 17 13.843 17H10.157C9.518 17 9 16.482 9 15.843C9 15.4177 8.82437 15.0112 8.51463 14.7196L7.41058 13.6805Z");
}

</style>
