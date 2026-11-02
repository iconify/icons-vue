<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-_x9sbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-bulk-sharp" /></template>
<style>
.s-_x9sbdw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 17a1 1 0 0 0-2 0v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0l8 8A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1Z");
}

</style>
