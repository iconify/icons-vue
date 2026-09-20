<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubsgv1b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:certificate-off-24-filled" /></template>
<style>
.ubsgv1b4n {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06L16.94 18H10v-1a5 5 0 0 0-8-6V5.75c0-.744.296-1.417.776-1.912L2.22 3.28a.75.75 0 0 1 0-1.06M9 21.249l-.007.104a.75.75 0 0 1-1.173.51l-1.819-1.272l-1.82 1.272l-.09.055A.75.75 0 0 1 3 21.249l.001-3.246A4.98 4.98 0 0 0 6 19a4.98 4.98 0 0 0 3.001-1zM6.001 10A4 4 0 1 1 6 18.001A4 4 0 0 1 6 10m13.25-7A2.75 2.75 0 0 1 22 5.75v9.5c0 .97-.503 1.819-1.26 2.309L11.68 8.5h5.57a.75.75 0 0 0 0-1.5h-7.07l-4-4z");
}

</style>
