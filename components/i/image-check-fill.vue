<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4o4z5a6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-check-fill" /></template>
<style>
.k4o4z5a6w {
  fill: currentColor;
  d: path("m17.414 22l-8.707-8.707a2.414 2.414 0 0 0-3.414 0L2 16.586V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3ZM14 10.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4a.999.999 0 1 0-1.414-1.414ZM3 18.414l3.707-3.707a.414.414 0 0 1 .586 0L14.586 22H5a3 3 0 0 1-2.975-2.611Z");
}

</style>
