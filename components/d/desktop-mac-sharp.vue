<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-n8inoga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-mac-sharp" /></template>
<style>
.x-n8inoga {
  fill: currentColor;
  d: path("M9.27 20v-.77l1.884-1.884H3V4h18v13.346h-8.154l1.885 1.885V20z");
}

</style>
