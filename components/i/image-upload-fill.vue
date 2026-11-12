<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7fxup7mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-upload-fill" /></template>
<style>
.s7fxup7mf {
  fill: currentColor;
  d: path("m17.414 22l-8.707-8.707a2.414 2.414 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3ZM14.293 5.293l-3 3a.999.999 0 1 0 1.414 1.414L14 8.414V12a1 1 0 0 0 2 0V8.414l1.293 1.293a.999.999 0 1 0 1.414-1.414l-3-3a1 1 0 0 0-1.414 0M3 18.414l3.707-3.707a.414.414 0 0 1 .586 0L14.586 22H5a3 3 0 0 1-2.975-2.611Z");
}

</style>
