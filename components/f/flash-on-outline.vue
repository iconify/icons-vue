<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn0g88y2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flash-on-outline" /></template>
<style>
.qn0g88y2z {
  fill: currentColor;
  d: path("m12 15.6l4.008-5.811h-3.331L14.35 4H9.385v8H12zm-1 3.246V13H8.385V3h7.288L14 8.789h3.904zM12 12H9.385z");
}

</style>
