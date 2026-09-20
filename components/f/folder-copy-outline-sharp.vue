<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tldilgbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-copy-outline-sharp" /></template>
<style>
.tldilgbgk {
  fill: currentColor;
  d: path("M2 19.77V7.076h1v11.692h16v1zm3-3V3h6.577l2 2H22v11.77zm1-1h15V6h-7.825l-2-2H6zm0 0V4z");
}

</style>
