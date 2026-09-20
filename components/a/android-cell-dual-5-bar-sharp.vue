<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v473h1b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-cell-dual-5-bar-sharp" /></template>
<style>
.v473h1b8b {
  fill: currentColor;
  d: path("M1 14V9.5h3V14zm4.75 0V8h3v6zm4.75 0V7h3v7zm4.75 0V6h3v8zM20 14V4h3v10zM1 20v-4h3v4zm4.75 0v-4h3v4zm4.75 0v-4h3v4zm4.75 0v-4h3v4zM20 20v-4h3v4z");
}

</style>
