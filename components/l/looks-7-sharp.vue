<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc88e0l9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-7-sharp" /></template>
<style>
.yc88e0l9j {
  fill: currentColor;
  d: path("M4 20V4h16v16zm7.462-3.5H12.5l2-7.936V7.5h-5v1h3.962z");
}

</style>
