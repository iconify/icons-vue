<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq97j7adm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-comment-outline-sharp" /></template>
<style>
.zq97j7adm {
  fill: currentColor;
  d: path("M11 14h2v-3h3V9h-3V6h-2v3H8v2h3zm-9 8V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
