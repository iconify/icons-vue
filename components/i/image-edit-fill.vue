<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urgm0t-re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-fill" /></template>
<style>
.urgm0t-re {
  fill: currentColor;
  d: path("m13.414 22l-6.707-6.707a2.415 2.415 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3Zm3.293-17.707a1 1 0 0 0-1.414 0l-5 5A1 1 0 0 0 10 10v3a1 1 0 0 0 1 1h3c.265 0 .52-.105.707-.293l5-5A1 1 0 0 0 20 8.001v-.002a1 1 0 0 0-.293-.706ZM4 17.414l.707-.707a.414.414 0 0 1 .586 0L10.586 22H5a3 3 0 0 1-2.975-2.611Z");
}

</style>
