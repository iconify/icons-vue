<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0rkb91ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:domain-disabled-outline-sharp" /></template>
<style>
.z0rkb91ul {
  fill: currentColor;
  d: path("m22 19.15l-2-2V9h-8.15L10 7.15V5H7.85l-2-2H12v4h10zm-1.5 4.15L18.15 21H2V4.8L.7 3.5l1.4-1.4l19.8 19.8zM4 19h2v-2H4zm0-4h2v-2H4zm0-4h2V9H4zm4 8h2v-2H8zm0-4h2v-2H8zm4 4h4.15l-2-2H12zm6-6h-2v-2h2z");
}

</style>
