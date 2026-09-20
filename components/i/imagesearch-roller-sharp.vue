<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7s06dbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:imagesearch-roller-sharp" /></template>
<style>
.j7s06dbso {
  fill: currentColor;
  d: path("M14.52 22h-4.116v-6.75h1.558v-4.5H3V4.5h2.923V3H19v4H5.923V5.5H4v4.25h8.962v5.5h1.557z");
}

</style>
