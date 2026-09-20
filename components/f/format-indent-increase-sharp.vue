<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs__4junw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-indent-increase-sharp" /></template>
<style>
.fs__4junw {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm8-3.75v-1h8v1zm0-3.75v-1h8v1zm0-3.75v-1h8v1zM4 5V4h16v1zm0 9.808V9.192L6.808 12z");
}

</style>
