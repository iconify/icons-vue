<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhreoxb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:density-medium-sharp" /></template>
<style>
.yhreoxb4k {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-7.5v-1h16v1zM4 5V4h16v1z");
}

</style>
