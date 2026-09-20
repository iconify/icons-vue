<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="abrhrbbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:brightness-low-32-filled" /></template>
<style>
.abrhrbbvw {
  fill: currentColor;
  d: path("M17 5a1 1 0 0 0-2 0v2a1 1 0 1 0 2 0zm6 11a7 7 0 1 1-14 0a7 7 0 0 1 14 0m-2 0a5 5 0 0 0-5-5v10a5 5 0 0 0 5-5m7 0a1 1 0 0 1-1 1h-2a1 1 0 1 1 0-2h2a1 1 0 0 1 1 1m-11 9a1 1 0 0 0-2 0v2a1 1 0 1 0 2 0zm-9-9a1 1 0 0 1-1 1H5a1 1 0 1 1 0-2h2a1 1 0 0 1 1 1m.707-8.707a1 1 0 0 0-1.414 1.414l1 1a1 1 0 0 0 1.414-1.414zM7.293 24.707a1 1 0 0 0 1.414 0l1-1a1 1 0 1 0-1.414-1.414l-1 1a1 1 0 0 0 0 1.414m16-17.414a1 1 0 0 1 1.414 1.414l-1 1a1 1 0 0 1-1.414-1.414zm0 17.414l-1-1a1 1 0 0 1 1.414-1.414l1 1a1 1 0 0 1-1.414 1.414");
}

</style>
