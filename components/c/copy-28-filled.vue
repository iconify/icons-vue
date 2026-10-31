<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wqawb2r6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-28-filled" /></template>
<style>
.wqawb2r6l {
  fill: currentColor;
  d: path("M10 16.25A4.75 4.75 0 0 0 14.75 21H17v1.25A3.75 3.75 0 0 1 13.25 26h-7.5A3.75 3.75 0 0 1 2 22.25v-10.5A3.75 3.75 0 0 1 5.75 8H10zM22.25 2A3.75 3.75 0 0 1 26 5.75v10.5A3.75 3.75 0 0 1 22.25 20h-7.5A3.75 3.75 0 0 1 11 16.25V5.75A3.75 3.75 0 0 1 14.75 2z");
}

</style>
