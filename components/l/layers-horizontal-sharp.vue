<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_m8k_bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-horizontal-sharp" /></template>
<style>
.s_m8k_bbh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.715 1.482L12 2L17.5 12L12 22L11.715 22.518M16.215 1.482L16.5 2L22 12L16.5 22L16.215 22.518M2 12L7.5 22L13 12L7.5 2L2 12Z");
}

</style>
