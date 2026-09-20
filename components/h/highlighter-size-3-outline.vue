<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itmlnabso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:highlighter-size-3-outline" /></template>
<style>
.itmlnabso {
  fill: currentColor;
  d: path("m8.096 19.404l-3.525-3.525q-.14-.14-.14-.354t.14-.354l10.575-10.6q.166-.165.379-.165t.354.165l3.525 3.55q.14.14.14.354t-.14.354L8.829 19.404q-.165.165-.366.165t-.367-.165");
}

</style>
