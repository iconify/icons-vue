<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="v7lu5ibpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:barcode-scanner-add-28-regular" /></template>
<style>
.v7lu5ibpi {
  fill: currentColor;
  d: path("M20.5 13a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M2.754 19a.75.75 0 0 1 .75.75v1.5a2.25 2.25 0 0 0 2.25 2.25H7.25a.75.75 0 0 1 0 1.5H5.754a3.75 3.75 0 0 1-3.75-3.75v-1.5a.75.75 0 0 1 .75-.75M20.5 15a.5.5 0 0 0-.5.5V19h-3.5a.5.5 0 0 0 0 1H20v3.5a.5.5 0 0 0 1 0V20h3.5a.5.5 0 0 0 0-1H21v-3.5a.5.5 0 0 0-.5-.5M7.254 8a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-1.5 0V8.75a.75.75 0 0 1 .75-.75m4.5 0a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-1.5 0V8.75a.75.75 0 0 1 .75-.75m4.5 0a.75.75 0 0 1 .75.75v4.114a7.5 7.5 0 0 0-1.5 1.043V8.75a.75.75 0 0 1 .75-.75m4.5 0a.75.75 0 0 1 .75.75v3.318a7.6 7.6 0 0 0-1.5-.05V8.75a.75.75 0 0 1 .75-.75M7.25 3a.75.75 0 0 1 0 1.5H5.754a2.25 2.25 0 0 0-2.25 2.25v1.5a.75.75 0 0 1-1.5 0v-1.5A3.75 3.75 0 0 1 5.754 3zm15.001 0a3.75 3.75 0 0 1 3.75 3.75v1.5a.75.75 0 0 1-1.5 0v-1.5a2.25 2.25 0 0 0-2.25-2.25H20.75a.75.75 0 0 1 0-1.5z");
}

</style>
