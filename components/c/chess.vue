<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb28ogbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess" /></template>
<style>
.cb28ogbiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 17l2-6H7L6 9l4-3l-1-3l3 1c3 1 4 4 4 7v6M6 19a2 2 0 0 1 2-2h8a2 2 0 1 1 0 4H8a2 2 0 0 1-2-2");
}

</style>
