<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfte6dbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-downward-alt-outline-rounded" /></template>
<style>
.gfte6dbyk {
  fill: currentColor;
  d: path("M11.5 15.392V6q0-.213.143-.357T12 5.5t.357.143T12.5 6v9.392l3.746-3.746q.14-.14.345-.15q.203-.01.363.15t.16.354t-.16.354l-4.389 4.388q-.242.243-.565.243t-.565-.243l-4.389-4.388q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16z");
}

</style>
