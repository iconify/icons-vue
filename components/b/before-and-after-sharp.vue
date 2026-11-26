<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdfcy61cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:before-and-after-sharp" /></template>
<style>
.fdfcy61cc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5L22 5L22 19L12 19M9 19L8 19L2 19L2 5L8 5L9 5M12 23L12 22L12 19L12 5L12 2L12 1");
}

</style>
