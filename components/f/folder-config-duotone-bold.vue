<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0jamibkm"/><path class="bn_pu6j-z"/><path class="pt-3kkb2k"/><path class="z8zjub4ii"/><path class="ae0h5kb0o"/><path class="c5u1kccgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-config-duotone-bold" /></template>
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

.pt-3kkb2k {
  d: path("M9 11h6");
}

.r0jamibkm {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z8zjub4ii {
  d: path("M13.5 9v4");
}

</style>
