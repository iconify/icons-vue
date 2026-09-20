<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuy21lbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brick-rounded" /></template>
<style>
.iuy21lbms {
  fill: currentColor;
  d: path("M3 17.789V9.923q0-.505.353-.858q.354-.353.858-.353h1.616v-2.5q0-.505.353-.859Q6.534 5 7.04 5h2.365q.505 0 .858.353q.354.354.354.859v2.5h2.769v-2.5q0-.51.353-.861T14.596 5h2.366q.504 0 .858.353q.353.354.353.859v2.5h1.616q.504 0 .858.353q.353.353.353.858v7.866q0 .504-.353.858q-.354.353-.858.353H4.211q-.505 0-.859-.353Q3 18.293 3 17.789");
}

</style>
