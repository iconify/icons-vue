<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohygplb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-out-fill" /></template>
<style>
.ohygplb3p {
  fill: currentColor;
  d: path("M15 17v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a.997.997 0 0 0-1-1H5a.997.997 0 0 0-1 1v14a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0m2.293-7.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 .009 1.405l-.008.008l-.001.001l-3 3a1 1 0 0 1-1.414-1.414L18.586 13H11a1 1 0 0 1 0-2h7.586Z");
}

</style>
