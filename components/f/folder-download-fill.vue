<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4my68bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-download-fill" /></template>
<style>
.d4my68bll {
  fill: currentColor;
  d: path("M12.414 5H19a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293Zm-1.121 11.707a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L13 13.586V10a1 1 0 0 0-2 0v3.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414Z");
}

</style>
