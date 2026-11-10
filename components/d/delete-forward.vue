<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou7bn_k_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:delete-forward" /></template>
<style>
.ou7bn_k_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 9L10 12M10 12L7 15M10 12L7 9M10 12L13 15M21.736 11.32L15.5942 4.65C15.2155 4.23 14.6817 4 14.1222 4H5C3.3431 4 2 5.34 2 7V17C2 18.66 3.3431 20 5 20H14.1222C14.6817 20 15.2155 19.77 15.5942 19.35L21.736 12.68C22.088 12.29 22.088 11.71 21.736 11.32Z");
}

</style>
