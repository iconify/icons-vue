<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7ixa1b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:first-page-rounded" /></template>
<style>
.h7ixa1b_a {
  fill: currentColor;
  d: path("M6.643 17.357Q6.5 17.214 6.5 17V7q0-.213.143-.357T7 6.5t.357.143T7.5 7v10q0 .214-.143.357T7 17.5t-.357-.143M13.108 12l4.246 4.246q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16l-4.388-4.389q-.131-.13-.184-.267q-.053-.136-.053-.298t.053-.298t.184-.267l4.388-4.389q.14-.14.345-.15q.203-.01.363.15t.16.354t-.16.354z");
}

</style>
