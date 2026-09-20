<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkjvg-bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:download-2-outline" /></template>
<style>
.mkjvg-bdb {
  fill: currentColor;
  d: path("M5 21v-1h14v1zm6.98-3.77L6.367 9.79h3.269V3h4.711v6.789h3.27zm0-1.634l3.574-4.788h-2.208V4h-2.711v6.808H8.427zm.02-4.788");
}

</style>
