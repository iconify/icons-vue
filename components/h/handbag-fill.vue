<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qszl3qpxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-fill" /></template>
<style>
.qszl3qpxy {
  fill: currentColor;
  d: path("M7.099 7a5.003 5.003 0 0 1 9.802 0H17c1.608 0 2.801 1.348 2.992 2.876l1 8c.121.968-.116 2.126-.925 2.752A1.75 1.75 0 0 1 19 21H5c-.389 0-.759-.135-1.067-.372c-.809-.626-1.046-1.784-.925-2.752l1-8C4.199 8.348 5.392 7 7 7ZM9.17 7h5.66a3.002 3.002 0 0 0-5.66 0");
}

</style>
