<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-hf8vdlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-arrow-right-sharp" /></template>
<style>
.d-hf8vdlx {
  fill: currentColor;
  d: path("M9 20v-7L1.95 4h18.1L13 13v7zm10-1l-1.4-1.4l1.575-1.6H15v-2h4.175L17.6 12.4L19 11l4 4zm-8-6.7L15.95 6h-9.9z");
}

</style>
