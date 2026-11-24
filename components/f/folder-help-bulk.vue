<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="awo3odbam"/><path class="e9ozfjbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-bulk" /></template>
<style>
.awo3odbam {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H19a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.e9ozfjbcl {
  d: path("M9.236 10.832A3 3 0 1 1 12 15a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 12a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M12.01 16a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
