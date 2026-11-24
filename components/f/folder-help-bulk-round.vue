<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2axkab4k"/><path class="e9ozfjbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-bulk-round" /></template>
<style>
.a2axkab4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H17a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.e9ozfjbcl {
  d: path("M9.236 10.832A3 3 0 1 1 12 15a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 12a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M12.01 16a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
