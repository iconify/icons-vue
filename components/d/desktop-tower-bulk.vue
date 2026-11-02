<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gqk_vr17m"/><path class="w6tlp5bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-tower-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gqk_vr17m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3Z");
}

.w6tlp5bmc {
  d: path("M17 7h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m-4 3H5a.997.997 0 0 0-1 1v4a1 1 0 0 0 1 1h8a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h8a1 1 0 0 1 0 2m5 6a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0ZM6 19h3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
