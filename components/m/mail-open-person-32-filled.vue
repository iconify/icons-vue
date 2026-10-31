<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ng4pfxbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-32-filled" /></template>
<style>
.ng4pfxbev {
  fill: currentColor;
  d: path("M28.583 24C29.918 24 31 25.103 31 26.438c0 2.023-1.714 4.062-6 4.062s-6-2.031-6-4.062C19 25.103 20.082 24 21.417 24zm-13.057-5.118a1 1 0 0 0 .949 0l4.1-2.21A5 5 0 0 0 20 19c0 1.363.546 2.598 1.43 3.5h-.013c-2.18 0-3.917 1.79-3.917 3.938q0 .282.031.563H6.5a4.5 4.5 0 0 1-4.5-4.5V12.018q0-.203.019-.405zM25 15.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M13.745 2.624a4.5 4.5 0 0 1 4.51 0l9.5 5.501c.662.383 1.202.92 1.587 1.552L16 16.865L2.653 9.685a4.5 4.5 0 0 1 1.592-1.56z");
}

</style>
