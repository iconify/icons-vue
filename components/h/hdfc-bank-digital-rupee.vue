<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l2nijxbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hdfc-bank-digital-rupee" /></template>
<style>
.l2nijxbxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 21V9.5a4 4 0 0 0-4-4H27m-6 0H9.5a4 4 0 0 0-4 4V21m0 6v11.5a4 4 0 0 0 4 4H21m6 0h11.5a4 4 0 0 0 4-4V27m-21.694 3.355a4.25 4.25 0 0 1-3.694 2.145h0a4.25 4.25 0 0 1-4.25-4.251v-2.763a4.25 4.25 0 0 1 4.25-4.251h0a4.25 4.25 0 0 1 4.252 4.25v1.382h-8.502M23.873 15.5h3.441c3.148 0 5.699 2.557 5.699 5.71s-2.551 5.712-5.698 5.712l5.698 5.578m-5.699-17h7.825m-11.266 5.739h11.266");
}

</style>
