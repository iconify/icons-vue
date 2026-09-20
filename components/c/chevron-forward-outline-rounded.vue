<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phnlay29j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chevron-forward-outline-rounded" /></template>
<style>
.phnlay29j {
  fill: currentColor;
  d: path("M13.292 12L9.046 7.754q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l4.388 4.389q.131.13.184.267t.053.298t-.053.298t-.184.268l-4.388 4.388q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354z");
}

</style>
