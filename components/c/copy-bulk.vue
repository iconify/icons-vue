<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mbpm__b1l"/><path class="nmh6pz_-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mbpm__b1l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.nmh6pz_-a {
  d: path("M19 2a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H7a1 1 0 0 1 0-2Z");
}

</style>
