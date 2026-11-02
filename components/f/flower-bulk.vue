<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qttdo8b4g"/><path class="v-cnqwb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flower-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qttdo8b4g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.101 5.101a4 4 0 0 1 7.798 0a4 4 0 0 1 0 7.798a4 4 0 0 1-7.798 0a4 4 0 0 1 0-7.798");
}

.v-cnqwb4y {
  d: path("M12 8h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m1 7v6a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0");
}

</style>
