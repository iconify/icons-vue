<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k111jlb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-nested-fill" /></template>
<style>
.k111jlb-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L5 4.5L3 6ZM5 10.5L7 12L5 13.5ZM7 18L9 19.5L7 21ZM9 4.5L21 4.5M11 12L21 12M13 19.5L21 19.5");
}

</style>
