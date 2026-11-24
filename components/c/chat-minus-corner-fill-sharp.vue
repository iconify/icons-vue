<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqxgr3bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-minus-corner-fill-sharp" /></template>
<style>
.gqxgr3bji {
  fill: currentColor;
  d: path("M10 10v7a1 1 0 0 1-1 1H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1Zm3 5h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
