<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yi_nl4bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-tree" /></template>
<style>
.yi_nl4bwr {
  d: path("M3.021 2.022h1.997v27.955H3.021zM28.98 27.98H5.018v1.997H28.98zm-6.99-8.985H5.019v1.997h16.973zM13.006 9.01H5.018v1.997h7.987z");
}

</style>
