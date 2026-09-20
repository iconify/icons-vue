<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c45m6rbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-bar-outline" /></template>
<style>
.c45m6rbno {
  fill: currentColor;
  d: path("M6 21v-2h5v-5L3 5V3h18v2l-8 9v5h5v2zM7.45 7h9.1l1.8-2H5.65zM12 12.1L14.775 9h-5.55zm0 0");
}

</style>
