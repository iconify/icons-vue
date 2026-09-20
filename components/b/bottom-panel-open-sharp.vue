<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0olfu_gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-panel-open-sharp" /></template>
<style>
.v0olfu_gb {
  fill: currentColor;
  d: path("M8.827 11.596h6.346L12 8.404zM5 15h14V5H5zm-1 5V4h16v16z");
}

</style>
