<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc2r4ounr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fast-forward-sharp" /></template>
<style>
.jc2r4ounr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6.002L10.4583 12L2 17.998L2 6.002ZM14 6.002L22 12L14 17.998L14 6.002Z");
}

</style>
