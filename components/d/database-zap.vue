<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yg2i_zb6r"/><path class="tb4djm5kx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-zap" /></template>
<style>
.tb4djm5kx {
  d: path("M3.5 5.5C3.5 7 6.85 8.25 11 8.25S18.5 7 18.5 5.5m-15 7c0 1.5 3.35 2.75 7.5 2.75c1.503 0 2.902-.164 4.074-.445M20.5 12.75l-4.25 5h4.5L16.5 22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yg2i_zb6r {
  d: path("M13.463 21.097c-.771.099-1.6.153-2.463.153c-4.15 0-7.5-1.25-7.5-2.75v-13C3.5 4 6.85 2.75 11 2.75S18.5 4 18.5 5.5v5.278");
}

</style>
