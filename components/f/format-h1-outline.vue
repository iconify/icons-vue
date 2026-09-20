<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs8l2q5kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h1-outline" /></template>
<style>
.zs8l2q5kq {
  fill: currentColor;
  d: path("M6 16.5v-9h1v4h5v-4h1v9h-1v-4H7v4zm11 0v-8h-2v-1h3v9z");
}

</style>
