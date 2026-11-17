<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jtvv-8ijy"/><path class="pjg41obyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-code-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jtvv-8ijy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Z");
}

.pjg41obyt {
  d: path("M4 6v8a1 1 0 0 0 .999 1H10a1 1 0 0 1 0 2H5c-1.657 0-3-1.342-3-2.998V6a3.004 3.004 0 0 1 2.999-3H11a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1m11.707 11.707L14.414 19l1.293 1.293a.999.999 0 1 1-1.414 1.414l-2-2a1 1 0 0 1 0-1.414l2-2a.999.999 0 1 1 1.414 1.414m4-1.414l2 2a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L19.586 19l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
