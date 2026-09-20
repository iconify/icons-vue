<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nfow-6bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-extract-32-filled" /></template>
<style>
.nfow-6bva {
  fill: currentColor;
  d: path("M17 9a3 3 0 0 0 3 3h7v15a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-4.5h8a2.5 2.5 0 0 0 0-5H5V5a3 3 0 0 1 3-3h9zm-6 15a1 1 0 1 0 0 2h10a1 1 0 1 0 0-2zm2-5a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm-2-5a1 1 0 1 0 0 2h10a1 1 0 1 0 0-2zm8-11.884c.484.14.93.4 1.293.763l5.828 5.828A3 3 0 0 1 26.884 10H20a1 1 0 0 1-1-1z");
}

</style>
