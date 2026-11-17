<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syfc46blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-3-horizontal-sharp" /></template>
<style>
.syfc46blm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 6.091L12 2L9.75 6.091M14.25 6.091L16.5 2L22 12L16.5 22L14.25 17.909M14.25 6.091L11 12L14.25 17.909M9.75 6.091L7.5 2L2 12L7.5 22L9.75 17.909M9.75 6.091L6.5 12L9.75 17.909M14.25 17.909L12 22L9.75 17.909");
}

</style>
