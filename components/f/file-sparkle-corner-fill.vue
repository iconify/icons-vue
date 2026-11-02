<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxi6uc58j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-sparkle-corner-fill" /></template>
<style>
.mxi6uc58j {
  fill: currentColor;
  d: path("M10 11v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1m7-3l-4-4v2a2 2 0 0 0 2 2Zm-1 5a1 1 0 0 1 2 0c0 1.452 1.548 3 3 3a1 1 0 0 1 0 2c-.774 0-1.508.422-2.043.957a3.5 3.5 0 0 0-.707.997c-.153.328-.25.683-.25 1.046a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 13 18a1 1 0 0 1 0-2c1.452 0 3-1.548 3-3");
}

</style>
