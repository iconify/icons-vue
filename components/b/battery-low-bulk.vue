<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nt9a1bc7y"/><path class="hn13l6b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-low-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hn13l6b8j {
  d: path("M7 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m15 0v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

.nt9a1bc7y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a3 3 0 0 1 3-3h11a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
