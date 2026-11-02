<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sjr9x5bay"/><path class="vcvs_zv8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-medium-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sjr9x5bay {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a4 4 0 0 1 4-4h9a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4Z");
}

.vcvs_zv8g {
  d: path("M7 14a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm3-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m12 4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
