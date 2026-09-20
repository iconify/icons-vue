<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7g38lbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-app-bar-outline-sharp" /></template>
<style>
.p7g38lbuq {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-4.5V19h14v-3.5h-5.146q-.329.43-.814.658q-.486.226-1.04.226t-1.04-.226q-.485-.227-.814-.658zm7.991-.509q.394-.393.394-.991t-.394-.991t-.991-.393t-.991.393t-.393.991t.393.991t.991.394t.991-.394M5 14.5h4.692q-.269-1.096.443-1.99q.711-.895 1.865-.895t1.866.894t.442 1.991H19V5H5zM5 19h14z");
}

</style>
