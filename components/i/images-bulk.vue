<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mbpm__b1l"/><path class="wvjgk6wyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:images-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mbpm__b1l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.wvjgk6wyt {
  d: path("M7 2h12a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H7a1 1 0 0 1 0-2M2.293 16.293l4-4a2.414 2.414 0 0 1 3.414 0l2 2a.414.414 0 0 0 .586 0a2.41 2.41 0 0 1 3.414 0l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.414.414 0 0 0-.586 0a2.41 2.41 0 0 1-3.414 0l-2-2a.414.414 0 0 0-.586 0l-4 4a.999.999 0 1 1-1.414-1.414");
}

</style>
