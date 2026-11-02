<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3un7pbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-check-corner-fill" /></template>
<style>
.m3un7pbys {
  fill: currentColor;
  d: path("M22 7v1H2V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3M2 10h8v9a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3Zm11.707 6.293l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414");
}

</style>
