<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b8egld_yp"/><path class="ux1vxzbsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-share-corner-bulk-round" /></template>
<style>
.b8egld_yp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 9a3 3 0 0 0-3 3v8a1 1 0 0 1-.804.981l-5 1a1 1 0 0 1-1.177-1.177l.935-4.673a9.943 9.943 0 0 1 17.94-8.578A1 1 0 0 1 20 9Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ux1vxzbsi {
  d: path("M21 14v4a1 1 0 0 1-2 0v-1.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L17.586 15H16a1 1 0 0 1 0-2h4a.997.997 0 0 1 1 1");
}

</style>
