<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcs06dbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-dashed-sharp" /></template>
<style>
.qcs06dbbg {
  fill: currentColor;
  d: path("M3 11.808V8.192h1v3.616zm0 8.269v-5.885h1v3.452L5.65 16h2.158v1H6.077zM10.192 17v-1h3.616v1zm6 0v-1H20v-1.808h1V17zM20 11.808V8.192h1v3.616zm0-5.994V4h-3.808V3H21v2.814zM10.192 4V3h3.616v1zM3 5.814V3h4.808v1H4v1.814z");
}

</style>
