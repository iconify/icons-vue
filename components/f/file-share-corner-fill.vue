<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isstt9bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-share-corner-fill" /></template>
<style>
.isstt9bym {
  fill: currentColor;
  d: path("m13.707 2.293l6 6A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293M13 4v2a2 2 0 0 0 2 2h2Zm8 14a1 1 0 0 1-2 0v-1.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L17.586 15H16a1 1 0 0 1 0-2h4a.997.997 0 0 1 1 1Z");
}

</style>
