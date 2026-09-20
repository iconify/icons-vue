<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9g6319tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:border-all-outline" /></template>
<style>
.p9g6319tx {
  fill: currentColor;
  d: path("M4 20V4h16v16zm15-1v-6.5h-6.5V19zm0-14h-6.5v6.5H19zM5 5v6.5h6.5V5zm0 14h6.5v-6.5H5z");
}

</style>
