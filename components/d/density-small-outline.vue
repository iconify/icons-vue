<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwx2fab_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:density-small-outline" /></template>
<style>
.vwx2fab_g {
  fill: currentColor;
  d: path("M4 21v-1h16v1zm0-5.673v-1h16v1zm0-5.654v-1h16v1zM4 4V3h16v1z");
}

</style>
