<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flsdn8ppi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-alert-outline-sharp" /></template>
<style>
.flsdn8ppi {
  fill: currentColor;
  d: path("M7.885 21V4.48h2.423V3h3.384v1.48h2.424V21zm1-1h6.23V5.462h-6.23zm0 0h6.23zm2.615-6.23h1v-5h-1zm.5 2.922q.31 0 .52-.21t.21-.52t-.21-.52t-.52-.211t-.52.21t-.21.52t.21.52t.52.211");
}

</style>
