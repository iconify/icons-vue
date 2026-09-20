<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afx_czbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:background-grid-small-outline-sharp" /></template>
<style>
.afx_czbwi {
  fill: currentColor;
  d: path("M5 19h2.75v-2.75H5zm3.75 0h2.75v-2.75H8.75zm3.75 0h2.75v-2.75H12.5zm3.75 0H19v-2.75h-2.75zM5 7.75h2.75V5H5zm0 3.75h2.75V8.75H5zm0 3.75h2.75V12.5H5zm3.75-7.5h2.75V5H8.75zm0 3.75h2.75V8.75H8.75zm0 3.75h2.75V12.5H8.75zm3.75-7.5h2.75V5H12.5zm0 3.75h2.75V8.75H12.5zm0 3.75h2.75V12.5H12.5zm3.75-7.5H19V5h-2.75zm0 3.75H19V8.75h-2.75zm0 3.75H19V12.5h-2.75zM4 20V4h16v16z");
}

</style>
