<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt_i70qsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bar-chart-4-bars" /></template>
<style>
.vt_i70qsl {
  fill: currentColor;
  d: path("M3 20v-1h18v1zm1-2.77V12h2v5.23zm4.654 0V7h2v10.23zm4.673 0V10h2v7.23zm4.673 0V4h2v13.23z");
}

</style>
