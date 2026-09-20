<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6swe7bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:float-portrait-2-sharp" /></template>
<style>
.m6swe7bil {
  fill: currentColor;
  d: path("M8.385 11.385h6v-5h-6zM19 21H5V3h14z");
}

</style>
