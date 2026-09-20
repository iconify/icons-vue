<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix3-3gksw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-break-right-outline" /></template>
<style>
.ix3-3gksw {
  fill: currentColor;
  d: path("M4 5V4h16v1zm7.5 11.25v-8.5H20v8.5zm1-1H19v-6.5h-6.5zM4 20v-1h16v1zm11.75-8");
}

</style>
