<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ci4d-ib1s"/><path class="qmy5ssbnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pin-corner-bulk" /></template>
<style>
.ci4d-ib1s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 6a2 2 0 0 0 2 2h2l-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.qmy5ssbnx {
  d: path("M12 3a1 1 0 0 1 1.698-.716l.009.008v.001l6 6A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3Zm2 4a.997.997 0 0 0 1 1h1.586L14 5.414Zm0 7a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2v1.586l.707.707c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14h-2v2a1 1 0 0 1-2 0v-2h-2a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l.707-.707Z");
}

</style>
