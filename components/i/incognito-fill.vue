<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otb71y0ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:incognito-fill" /></template>
<style>
.otb71y0ps {
  fill: currentColor;
  d: path("M3 11a1 1 0 0 1 0-2h2.323l1.749-4.371C7.394 3.823 8.056 3 9 3h6c.944 0 1.606.823 1.928 1.629L18.677 9H21a1 1 0 0 1 0 2Zm7.2 3.599a3.01 3.01 0 0 1 3.6 0A4 4 0 1 1 13 17v-.001A1 1 0 0 0 11 17a4 4 0 0 1-3.235 3.926a3.99 3.99 0 0 1-3.593-1.098a4 4 0 1 1 6.028-5.229m-1.357 1.623a2 2 0 1 0-3.686 1.556a2 2 0 0 0 3.686-1.556M15 17a2 2 0 1 0 3.999.001A2 2 0 0 0 15 17");
}

</style>
