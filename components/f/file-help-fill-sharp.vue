<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq08gdegc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-fill-sharp" /></template>
<style>
.mq08gdegc {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Zm-5 4a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 11 14a1 1 0 0 0 0 2a3 3 0 1 0-3-3m3.01 4H11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
