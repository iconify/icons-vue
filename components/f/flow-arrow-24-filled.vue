<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_pbrzyzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-arrow-24-filled" /></template>
<style>
.m_pbrzyzi {
  fill: currentColor;
  d: path("M5 2c1.306 0 2.414.835 2.826 2h8.924a4.25 4.25 0 0 1 0 8.5h-9.5a2.75 2.75 0 1 0 0 5.5h11.19l-1.72-1.72a.75.75 0 1 1 1.06-1.06l3 3a.75.75 0 0 1 0 1.06l-3 3a.75.75 0 1 1-1.06-1.06l1.72-1.72H7.25a4.25 4.25 0 0 1 0-8.5h9.5a2.75 2.75 0 1 0 0-5.5H7.958A3 3 0 1 1 5 2");
}

</style>
