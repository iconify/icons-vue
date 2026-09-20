<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuc5vcc5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-inset-sharp" /></template>
<style>
.yuc5vcc5q {
  fill: currentColor;
  d: path("M6.385 15.616h11.23V8.385H6.386zm2.23-1.885l1.799-2.402l1.163 1.555l1.587-2.115l2.22 2.962zM3 19V5h18v14z");
}

</style>
