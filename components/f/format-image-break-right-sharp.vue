<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9ym_tqos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-break-right-sharp" /></template>
<style>
.i9ym_tqos {
  fill: currentColor;
  d: path("M4 5V4h16v1zm7.5 11.25v-8.5H20v8.5zM4 20v-1h16v1z");
}

</style>
