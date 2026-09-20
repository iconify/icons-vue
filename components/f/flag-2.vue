<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8utxbseb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-2" /></template>
<style>
.n8utxbseb {
  fill: currentColor;
  d: path("M6 21V4h14l-2.096 4.27L20 12.538H7V21z");
}

</style>
