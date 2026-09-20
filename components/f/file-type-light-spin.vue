<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n8qupvb2w"/><path class="cbznf35ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-spin" /></template>
<style>
.cbznf35ej {
  d: path("M16 4.326A11.576 11.637 0 0 0 4.424 15.965A11.576 11.637 0 0 0 16 27.602a11.576 11.637 0 0 0 11.576-11.637A11.576 11.637 0 0 0 16 4.325m.035 2.797a8.831 8.878 0 0 1 8.832 8.877a8.831 8.878 0 0 1-8.832 8.879a8.831 8.878 0 0 1-8.83-8.88a8.831 8.878 0 0 1 8.83-8.876");
}

.n8qupvb2w {
  d: path("M11.012 2.002h2.9v27.997h-2.9z");
}

</style>
