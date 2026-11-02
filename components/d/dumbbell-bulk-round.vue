<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tss7snbwa"/><path class="sc-ep82on"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sc-ep82on {
  d: path("M9 13a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2Z");
}

.tss7snbwa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a3 3 0 1 1 6 0v10a3 3 0 1 1-6 0v-.171A3 3 0 0 1 2 14v-4c0-1.27.803-2.405 2-2.829Zm10 0a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 10v4c0 1.27-.803 2.405-2 2.829V17a3 3 0 1 1-6 0Z");
}

</style>
