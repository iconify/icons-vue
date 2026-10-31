<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="chfx78ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-20-filled" /></template>
<style>
.chfx78ble {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M7 11a4 4 0 0 0 2 3.464v.036c0 1.234.406 2.373 1.093 3.291A3 3 0 0 1 9 18H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2zm7.854 1.146a.5.5 0 1 0-.707.707L15.293 14H12.5a.5.5 0 0 0 0 1h2.793l-1.146 1.146a.5.5 0 1 0 .707.707l2.002-2.001a.5.5 0 0 0-.003-.706zM15 2a3 3 0 0 1 3 3v5.257a5.502 5.502 0 0 0-8.877 3.082A3 3 0 0 1 8 11V5a3 3 0 0 1 3-3z");
}

</style>
