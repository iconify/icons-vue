<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awnj3pb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-percent-corner-fill-sharp" /></template>
<style>
.awnj3pb8o {
  fill: currentColor;
  d: path("M19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h8c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10m-6-6v4h4Zm-1 10a2 2 0 1 1 3.999-.001A2 2 0 0 1 12 14m8.707.707l-6 6a.999.999 0 1 1-1.414-1.414l6-6a.999.999 0 1 1 1.414 1.414M18 20a2 2 0 1 1 3.999-.001A2 2 0 0 1 18 20");
}

</style>
