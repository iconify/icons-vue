<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhi03jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-4-bar-sharp" /></template>
<style>
.dhi03jbhp {
  fill: currentColor;
  d: path("M8.885 12h6.23V5.462h-6.23zm-1 9V4.48h2.423V3h3.384v1.48h2.424V21z");
}

</style>
