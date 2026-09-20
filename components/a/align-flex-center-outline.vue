<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okyyh3bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-flex-center-outline" /></template>
<style>
.okyyh3bbp {
  fill: currentColor;
  d: path("M11.692 21v-8H3.5v-2h8.192V3h1v8H20.5v2h-7.808v8z");
}

</style>
