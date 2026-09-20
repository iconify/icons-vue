<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-33jhb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-break-left-outline-sharp" /></template>
<style>
.v-33jhb-o {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V7h10v10zm2-2h6V9H5zM3 5V3h18v2zm5 7");
}

</style>
