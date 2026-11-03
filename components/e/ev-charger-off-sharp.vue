<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r01ui5bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-off-sharp" /></template>
<style>
.r01ui5bvw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 14L14 22L2 22L2 2M14 22L22 22M14 17L17 17M8.5714 8.5714L6 12L10 12L6.7 16.4M6.6569 2L14 2L14 9.3431M20 15.3431L20 10M18 6L22 6L22 10L18 10L18 6ZM22 6L22 3M18 6L18 3M1.7071 1.7071L22.2929 22.2929");
}

</style>
