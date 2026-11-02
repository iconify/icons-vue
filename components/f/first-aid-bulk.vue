<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v25atab7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:first-aid-bulk" /></template>
<style>
.v25atab7o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 8h3a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-3v3a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-3H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h3V5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3Z");
}

</style>
