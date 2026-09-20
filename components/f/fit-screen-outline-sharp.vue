<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adxbiabxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fit-screen-outline-sharp" /></template>
<style>
.adxbiabxp {
  fill: currentColor;
  d: path("M20 9V6h-3V5h4v4zM3 9V5h4v1H4v3zm14 10v-1h3v-3h1v4zM3 19v-4h1v3h3v1zm3.846-3.846V8.846h10.308v6.308zm1-1h8.308V9.846H7.846zm0 0V9.846z");
}

</style>
