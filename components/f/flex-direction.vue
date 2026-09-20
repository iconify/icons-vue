<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l719c3w6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flex-direction" /></template>
<style>
.l719c3w6m {
  fill: currentColor;
  d: path("M3 19v-5.808h7.846V19zm0-8.192V5h7.846v5.808zm1-1h5.846V6H4zM16.942 19l-4.288-4.288l.688-.689l3.1 3.056V5h1v12.079l3.1-3.056l.689.689z");
}

</style>
