<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o52dtgb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-extract-48-regular" /></template>
<style>
.o52dtgb_r {
  fill: currentColor;
  d: path("M24.758 4a4.25 4.25 0 0 1 3.005 1.245l10.992 10.992A4.25 4.25 0 0 1 40 19.242V39.75A4.25 4.25 0 0 1 35.75 44h-23.5A4.25 4.25 0 0 1 8 39.75V33.5h2.5v6.25c0 .967.784 1.75 1.75 1.75h23.5a1.75 1.75 0 0 0 1.75-1.75V20h-9.25A4.25 4.25 0 0 1 24 15.75V6.5H12.25a1.75 1.75 0 0 0-1.75 1.75V27H8V8.25A4.25 4.25 0 0 1 12.25 4zm6.992 31a1.25 1.25 0 1 1 0 2.5h-15.5a1.25 1.25 0 1 1 0-2.5zm-11-6a1.25 1.25 0 1 1 0 2.5H5.25a1.25 1.25 0 1 1 0-2.5zm11-6a1.25 1.25 0 1 1 0 2.5h-15.5a1.25 1.25 0 1 1 0-2.5zm-5.25-7.25c0 .966.784 1.75 1.75 1.75h8.232L26.5 7.518z");
}

</style>
