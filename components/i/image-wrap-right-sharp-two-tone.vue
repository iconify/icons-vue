<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="by7ngnb6r"/><path class="tamf82b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-wrap-right-sharp-two-tone" /></template>
<style>
.by7ngnb6r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 6L21 6C21.5523 6 22 6.4477 22 7L22 17C22 17.5523 21.5523 18 21 18L11 18C10.4477 18 10 17.5523 10 17L10 7C10 6.4477 10.4477 6 11 6Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tamf82b4i {
  d: path("M11 7L21 7L21 17L11 17ZM2 3L22 3M2 21L22 21M2 9L8 9M2 15L8 15");
}

</style>
