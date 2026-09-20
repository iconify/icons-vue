<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxrjj95qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apartment-outline" /></template>
<style>
.uxrjj95qy {
  fill: currentColor;
  d: path("M3.5 20.154v-13h4v-4h9v8h4v9h-7v-4h-3v4zm1-1h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 4h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 8h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 12h3v-3h-3zm0-4h3v-3h-3z");
}

</style>
