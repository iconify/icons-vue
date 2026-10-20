<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm94m0bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-sigma-two-tone" /></template>
<style>
.nm94m0bun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12ZM15.3282 7.0077L9.2276 7.0077C8.765 7.0077 8.5057 7.5404 8.7909 7.9045L11.7319 11.6579C11.8893 11.8588 11.8893 12.1412 11.7319 12.3421L8.7909 16.0955C8.5057 16.4596 8.765 16.9923 9.2276 16.9923L15.3282 16.9923");
}

</style>
