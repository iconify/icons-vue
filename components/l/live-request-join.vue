<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rj1lwzbap"/><path class="fjisffbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:live-request-join" /></template>
<style>
.fjisffbti {
  d: path("M5.5 14.5v3a4 4 0 0 0 4 4H11a3.5 3.5 0 0 0 3.5-3.5v-5m-6 3.5V11m3 5.5v-6");
}

.rj1lwzbap {
  d: path("M2.7 15.5h-.2v-13h19v13h-4.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
