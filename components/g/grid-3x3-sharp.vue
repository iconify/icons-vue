<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhg0dv4qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-3x3-sharp" /></template>
<style>
.zhg0dv4qn {
  fill: currentColor;
  d: path("M8 20v-4H4v-2h4v-4H4V8h4V4h2v4h4V4h2v4h4v2h-4v4h4v2h-4v4h-2v-4h-4v4zm2-6h4v-4h-4z");
}

</style>
