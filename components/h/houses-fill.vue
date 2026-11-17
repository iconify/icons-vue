<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc5rsv-pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-fill" /></template>
<style>
.xc5rsv-pj {
  fill: currentColor;
  d: path("M8 8.658V3a1 1 0 0 1 1-1h10a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6.717c0-.866.373-1.689 1.024-2.258l3-2.625A3 3 0 0 1 8 8.658M20 5a1 1 0 0 0-1-1h-9v5.421l2.976 2.604A3 3 0 0 1 14 14.283V20h6Zm-7 1h.01a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
