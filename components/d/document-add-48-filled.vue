<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxwkm9f6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-add-48-filled" /></template>
<style>
.mxwkm9f6u {
  fill: currentColor;
  d: path("M13 24c6.075 0 11 4.925 11 11s-4.925 11-11 11S2 41.075 2 35s4.925-11 11-11m11-8.75A3.75 3.75 0 0 0 27.75 19H40v22a3 3 0 0 1-3 3H22.376A12.95 12.95 0 0 0 26 35c0-7.18-5.82-13-13-13c-1.772 0-3.46.354-5 .996V7a3 3 0 0 1 3-3h13zM13 27a1 1 0 0 0-1 1v6H6a1 1 0 1 0 0 2h6v6a1 1 0 1 0 2 0v-6h6a1 1 0 1 0 0-2h-6v-6a1 1 0 0 0-1-1m26.462-10.5H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
