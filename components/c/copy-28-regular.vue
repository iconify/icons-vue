<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zkm_5ybpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-28-regular" /></template>
<style>
.zkm_5ybpm {
  fill: currentColor;
  d: path("M10 9.5H5.75a2.25 2.25 0 0 0-2.25 2.25v10.5a2.25 2.25 0 0 0 2.25 2.25h7.5a2.25 2.25 0 0 0 2.25-2.25V21H17v1.25A3.75 3.75 0 0 1 13.25 26h-7.5A3.75 3.75 0 0 1 2 22.25v-10.5A3.75 3.75 0 0 1 5.75 8H10zM22.25 2A3.75 3.75 0 0 1 26 5.75v10.5A3.75 3.75 0 0 1 22.25 20h-7.5A3.75 3.75 0 0 1 11 16.25V5.75A3.75 3.75 0 0 1 14.75 2zm-7.5 1.5a2.25 2.25 0 0 0-2.25 2.25v10.5a2.25 2.25 0 0 0 2.25 2.25h7.5a2.25 2.25 0 0 0 2.25-2.25V5.75a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
