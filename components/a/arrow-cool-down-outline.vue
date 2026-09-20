<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrg07l4or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-cool-down-outline" /></template>
<style>
.lrg07l4or {
  fill: currentColor;
  d: path("m12 21l-6.346-6.346l.688-.713l5.158 5.157v-7.117h1v7.136l5.158-5.152l.688.689zm-.5-11.02v-3h1v3zm0-5v-2h1v2z");
}

</style>
