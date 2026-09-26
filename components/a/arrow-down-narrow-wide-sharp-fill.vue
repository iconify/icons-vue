<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vscd-0bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-narrow-wide-sharp-fill" /></template>
<style>
.vscd-0bdi {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5L6 18M1.7071 13.7071L6 18L10.2929 13.7071M13 6L17 6M13 10L19 10M13 14L21 14M13 18L23 18");
}

</style>
