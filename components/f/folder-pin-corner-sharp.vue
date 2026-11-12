<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9lpghhzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-pin-corner-sharp" /></template>
<style>
.v9lpghhzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h9v2M8 20H3V4h7l2 2m3 7h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

</style>
