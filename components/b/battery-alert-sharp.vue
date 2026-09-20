<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zthq_hbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-alert-sharp" /></template>
<style>
.zthq_hbvd {
  fill: currentColor;
  d: path("M7.885 21V4.48h2.423V3h3.384v1.48h2.424V21zm3.615-7.23h1v-5h-1zm.5 2.922q.31 0 .52-.21t.21-.52t-.21-.52t-.52-.211t-.52.21t-.21.52t.21.52t.52.211");
}

</style>
