<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa4rg3b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:horizontal-align-right-outline-rounded" /></template>
<style>
.xa4rg3b3t {
  fill: currentColor;
  d: path("M19.143 18.857Q19 18.714 19 18.5v-13q0-.213.143-.357T19.5 5t.357.143T20 5.5v13q0 .214-.143.357T19.5 19t-.357-.143m-4.75-6.357H4.5q-.213 0-.357-.143T4 12t.143-.357t.357-.143h9.892l-2.746-2.746q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l3.388 3.388q.131.132.184.268q.053.137.053.298t-.053.298t-.184.268l-3.388 3.388q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354z");
}

</style>
