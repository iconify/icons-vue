<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="efm-cmbhw"/><path class="jcg6987yn"/><path class="k2kp2g75r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-reorder" /></template>
<style>
.efm-cmbhw {
  d: path("M9.541 21.176A9.5 9.5 0 0 1 7.985 3.39m6.474-.566a9.5 9.5 0 0 1 1.556 17.786");
}

.jcg6987yn {
  d: path("M21.5 5.25L20.5 8l-2.75-1M2.5 18.75l1-2.75l2.75 1M12 6.5l4.75 2.75v5.5L12 17.5l-4.75-2.75v-5.5Z");
}

.k2kp2g75r {
  d: path("M7.25 9.25L12 12l4.75-2.75M12 12v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
