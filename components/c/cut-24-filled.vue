<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbe2oabiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cut-24-filled" /></template>
<style>
.dbe2oabiy {
  fill: currentColor;
  d: path("M7.83 2.44a1 1 0 0 0-1.66 1.117l4.793 7.114l-2.326 3.678a4 4 0 1 0 1.57 1.26l1.977-3.126l1.884 2.796a4 4 0 1 0 1.683-1.08l-3.62-5.375v.001zM5 18a2 2 0 1 1 4 0a2 2 0 0 1-4 0m10 0a2 2 0 1 1 4 0a2 2 0 0 1-4 0m-.48-9.21l3.325-5.256a1 1 0 0 0-1.69-1.07L13.3 6.979z");
}

</style>
