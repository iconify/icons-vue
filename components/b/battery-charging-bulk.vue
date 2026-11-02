<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nt9a1bc7y"/><path class="v-6q2uxkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-charging-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nt9a1bc7y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a3 3 0 0 1 3-3h11a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.v-6q2uxkc {
  d: path("m11.707 10.707l-.293.293H12a1.002 1.002 0 0 1 .707 1.707l-2 2a.999.999 0 1 1-1.414-1.414L9.586 13H9a1.002 1.002 0 0 1-.707-1.707l2-2a.999.999 0 1 1 1.414 1.414M22 14a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
