<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb1t6ctqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keep-off-outline-sharp" /></template>
<style>
.gb1t6ctqw {
  fill: currentColor;
  d: path("M17 3v2h-1v8.175l-2-2V5h-4v2.175L7.825 5L7 4.175V3zm-5 20l-1-1v-6H6v-2l2-2v-1.15L1.4 4.2l1.4-1.4l18.4 18.4l-1.45 1.4l-6.6-6.6H13v6zm-3.15-9h2.3l-1.1-1.1l-.05-.05zm1.2-1.1");
}

</style>
