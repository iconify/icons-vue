<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stub05b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bluetooth-disabled" /></template>
<style>
.stub05b_k {
  fill: currentColor;
  d: path("m19.8 22.6l-4.2-4.2L12 22h-1v-7.6L6.4 19L5 17.6l4.9-4.9l-8.5-8.5l1.4-1.4l18.4 18.4zM13 18.15L14.15 17L13 15.85zm1.1-6.85l-1.4-1.4l2.2-2.2L13 5.85v4.35l-2-2V2h1l5.7 5.7z");
}

</style>
