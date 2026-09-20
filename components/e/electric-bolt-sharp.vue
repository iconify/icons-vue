<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4l9feqgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:electric-bolt-sharp" /></template>
<style>
.j4l9feqgh {
  fill: currentColor;
  d: path("m7 22l4-7.5l-8-1L15 2h2l-4 7.5l8 1L9 22z");
}

</style>
