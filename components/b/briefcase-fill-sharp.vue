<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy3nmg1fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:briefcase-fill-sharp" /></template>
<style>
.wy3nmg1fg {
  fill: currentColor;
  d: path("M7.099 7a5.003 5.003 0 0 1 9.802 0H21a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1ZM9.17 7h5.66a3.002 3.002 0 0 0-5.66 0");
}

</style>
