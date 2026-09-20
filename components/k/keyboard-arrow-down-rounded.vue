<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz4enkbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-arrow-down-rounded" /></template>
<style>
.jz4enkbah {
  fill: currentColor;
  d: path("M11.702 14.326q-.136-.053-.267-.184L7.046 9.754q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16L12 13.292l4.246-4.246q.14-.14.345-.15q.203-.01.363.15t.16.354t-.16.354l-4.389 4.388q-.13.131-.267.184q-.136.053-.298.053t-.298-.053");
}

</style>
