<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bn_pu6j-z"/><path class="pt-3kkb2k"/><path class="z8zjub4ii"/><path class="ae0h5kb0o"/><path class="c5u1kccgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-config-outline-regular" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.c5u1kccgl {
  d: path("M10.5 13v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.z8zjub4ii {
  d: path("M13.5 9v4");
}

</style>
