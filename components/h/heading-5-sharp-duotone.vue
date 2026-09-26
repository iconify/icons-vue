<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ouh-gobdj"/><path class="djlxqvhyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-5-sharp-duotone" /></template>
<style>
.djlxqvhyq {
  d: path("M22 13L17 13L17 16L19 16C20.1046 16 21 16.8954 21 18C21 19.1046 20.1046 20 19 20C18.2855 20 17.3573 19.6188 17 19L16.7113 18.5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ouh-gobdj {
  stroke-opacity: 0.4;
  d: path("M2 3L2 21M11 3L11 21M2 12L11 12");
}

</style>
