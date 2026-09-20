<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0295bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:expand-more-rounded" /></template>
<style>
.vs0295bgk {
  fill: currentColor;
  d: path("M12 14.373q-.161 0-.298-.053t-.267-.184L7.046 9.749q-.14-.14-.15-.344t.15-.363t.354-.16t.354.16L12 13.287l4.246-4.246q.14-.141.345-.15q.203-.01.363.15q.16.159.16.353t-.16.354l-4.389 4.389q-.13.13-.267.183q-.136.053-.298.053");
}

</style>
