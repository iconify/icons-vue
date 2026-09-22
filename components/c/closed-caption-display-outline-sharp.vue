<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrdtwjrtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:closed-caption-display-outline-sharp" /></template>
<style>
.vrdtwjrtl {
  fill: currentColor;
  d: path("M5 18V6zm1-9v6h3v-1.5H7.5v-3h2v.5H11V9zm7 0v3h1.5v-1.5h2v.5H18V9zM3 20V4h18v8h-2V6H5v12h4v2zm8 2v-8h11v8zm2-2h7v-4h-7z");
}

</style>
