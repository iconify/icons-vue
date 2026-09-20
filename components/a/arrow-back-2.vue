<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4a22tbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-back-2" /></template>
<style>
.j4a22tbhd {
  fill: currentColor;
  d: path("M15 17.192L6.846 12L15 6.808z");
}

</style>
