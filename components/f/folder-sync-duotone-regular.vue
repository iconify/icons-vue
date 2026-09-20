<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r0jamibkm"/><path class="bn_pu6j-z"/><path class="ioj0a6btg"/><path class="oav48zkig"/><path class="woh6qyb5h"/><path class="cd54abpwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-sync-duotone-regular" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.cd54abpwo {
  d: path("m11.5 13 -2 2 2 2");
}

.ioj0a6btg {
  d: path("M9 11.5h5.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oav48zkig {
  d: path("m12.5 9.5 2 2 -2 2");
}

.r0jamibkm {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.woh6qyb5h {
  d: path("M9.5 15H15");
}

</style>
