<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r69t8ubop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d10-sharp" /></template>
<style>
.r69t8ubop {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2.0016L21.9984 12L12 21.9984L2.0016 12ZM8 12L12 2L16 12L12 16ZM2 12L8 12M16 12L22 12M12 16L12 22");
}

</style>
