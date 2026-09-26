<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe3qplk3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:handbag" /></template>
<style>
.xe3qplk3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7C8 4.790861 9.790861 3 12 3C14.209139 3 16 4.790861 16 7M7 7L17 7C18.656854 7 20 8.343146 20 10L20 18C20 19.656854 18.656854 21 17 21L7 21C5.343146 21 4 19.656854 4 18L4 10C4 8.343146 5.343146 7 7 7Z");
}

</style>
