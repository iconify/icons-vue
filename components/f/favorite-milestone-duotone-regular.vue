<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vjajq6_sv"/><path class="ftqzjnb8u"/><path class="g_dn-kxhf"/><path class="euckimbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:favorite-milestone-duotone-regular" /></template>
<style>
.euckimbze {
  d: path("M9 8a1.5 1.5 0 0 1 3 0 1.5 1.5 0 0 1 3 0l-3 3Z");
}

.ftqzjnb8u {
  d: path("M6 3v18");
}

.g_dn-kxhf {
  d: path("M6 4h12v10H6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vjajq6_sv {
  fill: currentColor;
  d: path("M9 8a1.5 1.5 0 0 1 3 0 1.5 1.5 0 0 1 3 0l-3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
