<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmgrt2w7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-fill" /></template>
<style>
.gmgrt2w7v {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-1.269-1.269C19.429 21.83 18.707 22 18 22H6a3.004 3.004 0 0 1-3-3V7c0-.707.17-1.429.562-2.024L1.293 2.707a.999.999 0 1 1 1.414-1.414M15 3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v7a1 1 0 0 1-2 0v-4h-4.757l-6-6H15Zm-6.414 7H5v9a1 1 0 0 0 1 1h12c.176 0 .353-.018.523-.062Z");
}

</style>
