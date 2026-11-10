<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucz__osii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-compact-four-directions-sharp" /></template>
<style>
.ucz__osii {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.297 15.45L2 12L4.297 8.55M15.445 19.7L12 22L8.555 19.7M19.703 15.45L22 12L19.703 8.55M15.445 4.3L12 2L8.555 4.3");
}

</style>
