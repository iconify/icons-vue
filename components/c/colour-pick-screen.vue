<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aq12phbdx"/><path class="zc5btpt9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-pick-screen" /></template>
<style>
.aq12phbdx {
  d: path("M3.25 7.75v-2.5a2 2 0 0 1 2-2h2.5m6 0h2.5a2 2 0 0 1 2 2v2.5m-15 6v2.5a2 2 0 0 0 2 2h2.5m.5-10l2 2m1.055-1.066l6.011 6.011l-2.121 2.121l-6.011-6.011Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zc5btpt9p {
  d: path("m17.573 14.745l3.182 3.182l-2.828 2.828l-3.182-3.182Z");
}

</style>
