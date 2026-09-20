<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aphehzb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:1k-outline" /></template>
<style>
.aphehzb5p {
  fill: currentColor;
  d: path("M12.539 14.692h.884v-2.365l2.289 2.365h1.229l-2.652-2.73l2.651-2.654h-1.19l-2.327 2.326V9.308h-.885zm-3.731 0h.884V9.308H7.308v.884h1.5zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14z");
}

</style>
