<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv1pijluh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-down-sharp" /></template>
<style>
.iv1pijluh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 2L18 21M21.2929 17.7071L18 21L14.7071 17.7071M6 22L6 3M9.2929 6.2929L6 3L2.7071 6.2929");
}

</style>
