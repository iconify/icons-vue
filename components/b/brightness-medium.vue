<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo9uq2bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:brightness-medium" /></template>
<style>
.wo9uq2bbe {
  fill: currentColor;
  d: path("M20 15.31L23.31 12L20 8.69V4h-4.69L12 .69L8.69 4H4v4.69L.69 12L4 15.31V20h4.69L12 23.31L15.31 20H20zM12 18V6c3.31 0 6 2.69 6 6s-2.69 6-6 6");
}

</style>
