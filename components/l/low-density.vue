<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0gh8kv1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:low-density" /></template>
<style>
.g0gh8kv1q {
  fill: currentColor;
  d: path("M4 20v-8.615h1V19h14V5h-7.615V4H20v16zM4 8.923v-1.23h1.23v1.23zm0-3.692V4h1.23v1.23zm3.692 7.385v-1.231h1.231v1.23zm0-7.385V4h1.231v1.23zm3.692 7.385v-1.231h1.231v1.23zm0-3.693v-1.23h1.231v1.23z");
}

</style>
