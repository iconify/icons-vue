<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb4-twkxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-outline-sharp" /></template>
<style>
.jb4-twkxv {
  fill: currentColor;
  d: path("M4 20V4h6.252q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985H20v16zm1-1h14V5h-3v2.23H8V5H5zm7.578-14.003q.23-.233.23-.577t-.234-.575t-.577-.23t-.575.233t-.23.578t.233.575t.578.23t.575-.234");
}

</style>
