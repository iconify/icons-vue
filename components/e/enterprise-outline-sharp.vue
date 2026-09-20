<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvk37gzvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:enterprise-outline-sharp" /></template>
<style>
.tvk37gzvd {
  fill: currentColor;
  d: path("M12 15.5q.825 0 1.413-.587T14 13.5t-.587-1.412T12 11.5t-1.412.588T10 13.5t.588 1.413T12 15.5M2 21V6h6V2h8v4h6v15zm2-2h16V8H4zm6-13h4V4h-4zM4 19V8z");
}

</style>
