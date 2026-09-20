<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro3e8mxqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-arrow-rounded" /></template>
<style>
.ro3e8mxqs {
  fill: currentColor;
  d: path("M13.429 16.044q-.404.268-.82.032q-.417-.236-.417-.728V12.5H3.577q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h8.615V8.652q0-.492.417-.728q.416-.236.82.032l5.285 3.367q.378.238.378.675t-.378.679z");
}

</style>
