<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ltvp4bbbj"/><path class="r226xsbyq"/><path class="kqj26io4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:brain-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqj26io4i {
  d: path("M9.34699 10.1999C7.98371 10.7054 6.53659 10.0275 6.11475 8.68582M8.45587 17.2585C7.0926 17.764 5.64547 17.0861 5.22363 15.7444M14.1554 10.1999C15.5186 10.7054 16.9658 10.0275 17.3876 8.68582M15.0465 17.2585C16.4097 17.764 17.8569 17.0861 18.2787 15.7444");
}

.ltvp4bbbj {
  d: path("M11.7509 18.741C11.7509 19.1375 11.5995 22.0306 7.99889 21.9998C3.49813 21.9614 0.122706 16.1828 2.5739 12.1378C1.82374 10.7123 1.1512 7.46073 4.46233 5.85814C4.42387 3.65296 6.71718 2.04115 8.74963 2.00088C10.1826 1.97248 11.7509 3.2091 11.7509 4.60204V18.741Z");
}

.r226xsbyq {
  d: path("M11.7511 18.741C11.7511 19.1375 11.9025 22.0306 15.5031 21.9998C20.0038 21.9614 23.3792 16.1828 20.928 12.1378C21.6782 10.7123 22.3507 7.46073 19.0396 5.85814C19.0781 3.65296 16.7848 2.04115 14.7523 2.00088C13.3194 1.97248 11.7511 3.2091 11.7511 4.60204V18.741Z");
}

</style>
