<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jw_yhbbxl"/><path class="w_g6mqbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-bak" /></template>
<style>
.jw_yhbbxl {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M20.414 2H5v28h22V8.586ZM7 28V4h12v6h6v18Z");
}

.w_g6mqbtu {
  fill: var(--svg-color--99b8c4, #99b8c4);
  d: path("M20.856 9.659a10.74 10.74 0 0 1 7.893 3.249A10.74 10.74 0 0 1 32 20.8a10.74 10.74 0 0 1-3.25 7.891a10.74 10.74 0 0 1-7.893 3.249a10.7 10.7 0 0 1-6.789-2.321l1.74-1.74a8.84 8.84 0 0 0 5.049 1.568a8.624 8.624 0 0 0 8.648-8.647a8.624 8.624 0 0 0-8.649-8.647a8.624 8.624 0 0 0-8.649 8.647h3.714l-4.99 4.934L6 20.8h3.713a10.74 10.74 0 0 1 3.25-7.891a10.76 10.76 0 0 1 7.893-3.25");
}

</style>
