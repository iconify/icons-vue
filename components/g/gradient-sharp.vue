<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz6pjvb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gradient-sharp" /></template>
<style>
.wz6pjvb3z {
  fill: currentColor;
  d: path("M3 21V3h18v18zm8-10v2h2v-2zm-4 0v2h2v-2zm2 2v2h2v-2zm4 0v2h2v-2zm-8 0v2h2v-2zm10-2v2h2v2h2v-2h-2v-2zm-8 4v2H5v2h2v-2h2v2h2v-2h2v2h2v-2h2v2h2v-2h-2v-2h-2v2h-2v-2h-2v2H9v-2zm12-4v2zm0 4v2z");
}

</style>
