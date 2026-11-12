<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq-me3xvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-round" /></template>
<style>
.lq-me3xvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16.5 14l-3.162 3.513a1.8 1.8 0 0 1-2.676 0L4.27 10.41a2 2 0 0 1 .073-2.752l1.486-1.486A4 4 0 0 1 8.657 5h6.686a4 4 0 0 1 2.829 1.172l1.486 1.486a2 2 0 0 1 .073 2.752zM8 9l2 2");
}

</style>
