<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3qifbbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:density-large" /></template>
<style>
.i3qifbbpu {
  fill: currentColor;
  d: path("M4 20v-1h16v1zM4 5V4h16v1z");
}

</style>
