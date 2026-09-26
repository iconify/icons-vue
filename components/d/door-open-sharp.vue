<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i026q6bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:door-open-sharp" /></template>
<style>
.i026q6bbu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 4L14 2L14 22L6 19.68L6 4ZM18 21L18 3L14 3M1 21L10.5517 21M14 21L23 21M11 10L11 14");
}

</style>
