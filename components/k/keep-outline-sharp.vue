<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woaf_gbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keep-outline-sharp" /></template>
<style>
.woaf_gbfa {
  fill: currentColor;
  d: path("m16 12l2 2v2h-5v6l-1 1l-1-1v-6H6v-2l2-2V5H7V3h10v2h-1zm-7.15 2h6.3L14 12.85V5h-4v7.85zM12 14");
}

</style>
