<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofy7-i9sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-9-outline-sharp" /></template>
<style>
.ofy7-i9sk {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5zm5.5-2.5h4v-9h-5v5h4v3h-3zm3-5h-3v-3h3z");
}

</style>
