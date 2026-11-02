<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw0d_vcpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-upload-fill" /></template>
<style>
.uw0d_vcpy {
  fill: currentColor;
  d: path("M12.414 5H19a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293ZM13 12.414l1.293 1.293a.999.999 0 1 0 1.414-1.414l-3-3a1 1 0 0 0-1.414 0l-3 3a.999.999 0 1 0 1.414 1.414L11 12.414V16a1 1 0 0 0 2 0Z");
}

</style>
