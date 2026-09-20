<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h967h1b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-view-sharp" /></template>
<style>
.h967h1b_v {
  fill: currentColor;
  d: path("M4 11V4h7v7zm0 9v-7h7v7zm9-9V4h7v7zm0 9v-7h7v7z");
}

</style>
