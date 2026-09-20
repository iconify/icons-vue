<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kucxl_qmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-split-right-focus-left-24-filled" /></template>
<style>
.kucxl_qmy {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75zm9-1.75v6.75h7.5v-5a1.75 1.75 0 0 0-1.75-1.75zm0 8.25v6.75h5.75a1.75 1.75 0 0 0 1.75-1.75v-5z");
}

</style>
