<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdm3eve5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-vertical-center-outline" /></template>
<style>
.fdm3eve5q {
  fill: currentColor;
  d: path("M7.596 20v-7.5H3v-1h4.596V4h2.039v7.5h4.73V7h2.039v4.5H21v1h-4.596V17h-2.039v-4.5h-4.73V20z");
}

</style>
