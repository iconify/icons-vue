<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qktr83u_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-sharp" /></template>
<style>
.qktr83u_a {
  fill: currentColor;
  d: path("M3 21V3h18v18zm5.076-7.46q-.23-.23-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23t-.539-.23m6.77 0q-.23-.23-.23-.54t.23-.54t.539-.23t.539.23t.23.54t-.23.54t-.54.23t-.539-.23M6 11.254V17.5h1v-2h10v2h1v-6.246L16.344 6.5H7.656zm1.304-.754l1.046-3h7.3l1.046 3z");
}

</style>
