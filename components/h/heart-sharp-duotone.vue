<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlcuecc1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-sharp-duotone" /></template>
<style>
.dlcuecc1y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21C7.4376 17.1033 2 13.75 2 8.75C2 5.5743 4.6862 3 8 3C9.5 3 10.8426 3.5459 12 4.5C13.1574 3.5459 14.5 3 16 3C19.3138 3 22 5.5743 22 8.75C22 13.75 16.5624 17.1033 12 21Z");
}

</style>
