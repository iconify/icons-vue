<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg0fbwbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:imagesearch-roller-outline-sharp" /></template>
<style>
.bg0fbwbzf {
  fill: currentColor;
  d: path("M14.52 22h-4.116v-6.75h1.558v-4.5H3V4.5h2.923V3H19v4H5.923V5.5H4v4.25h8.962v5.5h1.557zm-3.116-1h2.115v-4.75h-2.115zM6.923 6H18V4H6.923zm4.48 15h2.116zM6.924 6V4z");
}

</style>
