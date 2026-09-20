<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go3gt_bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-app-logo" /></template>
<style>
.go3gt_bez {
  fill: currentColor;
  d: path("M6.366 20q-.986 0-1.676-.69T4 17.635V12q0-.47.176-.9t.507-.763l5.634-5.635q.349-.354.79-.528T12 4q.45 0 .88.17q.431.171.783.532l1.02 1.02l-6.933 6.932v3.596h8.5v-3.596L12.689 9.11l2.702-2.696l3.907 3.922q.329.329.516.76T20 12v5.635q0 .985-.695 1.675q-.696.69-1.69.69z");
}

</style>
