<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vccor0bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:in-home-mode-outline-sharp" /></template>
<style>
.vccor0bkt {
  fill: currentColor;
  d: path("M5 19V9.452l-2.396 1.779l-.598-.787L12 3l10.02 7.439l-.604.792L12 4.25L6 8.716V18h2.673v1zm9.637 2l-3.533-3.538l.708-.714l2.825 2.825l5.675-5.65l.688.714z");
}

</style>
