<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yuhbr1qrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:headlights-light" /></template>
<style>
.yuhbr1qrp {
  fill: currentColor;
  d: path("M162 80a6 6 0 0 1 6-6h72a6 6 0 0 1 0 12h-72a6 6 0 0 1-6-6m78 90h-72a6 6 0 0 0 0 12h72a6 6 0 0 0 0-12m0-64h-72a6 6 0 0 0 0 12h72a6 6 0 0 0 0-12m0 32h-72a6 6 0 0 0 0 12h72a6 6 0 0 0 0-12m-98-74v128a14 14 0 0 1-14 14H88a78 78 0 0 1-78-78.59C10.32 84.73 45.71 50 88.9 50H128a14 14 0 0 1 14 14m-12 0a2 2 0 0 0-2-2H88.9C52.28 62 22.27 91.38 22 127.5A66 66 0 0 0 88 194h40a2 2 0 0 0 2-2Z");
}

</style>
