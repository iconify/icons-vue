<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbfk6-b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-cell-4-bar-off" /></template>
<style>
.lbfk6-b-v {
  fill: currentColor;
  d: path("m20.285 20.233l-4.689-3.283V19h-1.692v-3.227l-3.827-2.696V19H8.384v-7.1L1.443 7.035l.848-1.218L21.133 19.01zm.83-4.299l-1.692-1.195V5h1.693zM2.866 19v-6.577h1.693V19zm12.731-6.939l-1.692-1.177V7.79h1.692z");
}

</style>
