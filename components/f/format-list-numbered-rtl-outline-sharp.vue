<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryuadtgwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-list-numbered-rtl-outline-sharp" /></template>
<style>
.ryuadtgwt {
  fill: currentColor;
  d: path("M17 22v-1.5h2.5v-.75H18v-1.5h1.5v-.75H17V16h4v2.25L20 19l1 .75V22zm0-7v-3.75h2.5v-.75H17V9h4v3.75h-2.5v.75H21V15zm1.5-7V3.5H17V2h3v6zM3 19v-2h12v2zm0-6v-2h12v2zm0-6V5h12v2z");
}

</style>
