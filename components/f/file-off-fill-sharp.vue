<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stb_021qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-off-fill-sharp" /></template>
<style>
.stb_021qu {
  fill: currentColor;
  d: path("M20 17.757L4.425 2.182C4.593 2.064 4.794 2 5 2h8c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9ZM2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414L18.586 22H5a1 1 0 0 1-1-1V7.414L1.293 4.707a.999.999 0 1 1 1.414-1.414M13 9h5l-5-5Z");
}

</style>
