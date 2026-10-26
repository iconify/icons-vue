<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqbvs_bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fire-extinguisher" /></template>
<style>
.vqbvs_bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11C8 8.7909 9.7909 7 12 7C14.2091 7 16 8.7909 16 11L16 19C16 20.1046 15.1046 21 14 21L10 21C8.8954 21 8 20.1046 8 19L8 11ZM14 5C14 6.1046 13.1046 7 12 7C10.8954 7 10 6.1046 10 5C10 3.8954 10.8954 3 12 3C13.1046 3 14 3.8954 14 5ZM8 16L16 16M14 5L18 5M18 5L20 3M18 5L20 7M10 5C6.6863 5 4 7.6863 4 11L4 20M8 16L4 16");
}

</style>
