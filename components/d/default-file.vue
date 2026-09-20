<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jw_yhbbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:default-file" /></template>
<style>
.jw_yhbbxl {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M20.414 2H5v28h22V8.586ZM7 28V4h12v6h6v18Z");
}

</style>
