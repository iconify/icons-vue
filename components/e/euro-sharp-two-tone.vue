<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llh2edb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:euro-sharp-two-tone" /></template>
<style>
.llh2edb5w {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21.4 19.7L21 20C19.269 21.2982 17.1637 22 15 22C9.4772 22 5 17.5228 5 12C5 6.4772 9.4772 2 15 2C17.1637 2 19.269 2.7018 21 4L21.4 4.3M2 10L3 10L17 10L18 10M2 14L3 14L17 14L18 14");
}

</style>
