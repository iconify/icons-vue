<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkk6-bz_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-top-24-regular" /></template>
<style>
.rkk6-bz_o {
  fill: currentColor;
  d: path("M3 6.25a.75.75 0 0 0 1.5 0v-.5c0-.69.56-1.25 1.25-1.25h12.5c.69 0 1.25.56 1.25 1.25v.5a.75.75 0 0 0 1.5 0v-.5A2.75 2.75 0 0 0 18.25 3H5.75A2.75 2.75 0 0 0 3 5.75zm1.5 4.5a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 1.5 0zm15 0a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-1.5 0zm-5.5 9.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h2.5a.75.75 0 0 1 .75.75M6.25 21a.75.75 0 0 0 0-1.5h-.5c-.69 0-1.25-.56-1.25-1.25v-.5a.75.75 0 0 0-1.5 0v.5A2.75 2.75 0 0 0 5.75 21zM17 20.25c0 .414.336.75.75.75h.5A2.75 2.75 0 0 0 21 18.25v-.5a.75.75 0 0 0-1.5 0v.5c0 .69-.56 1.25-1.25 1.25h-.5a.75.75 0 0 0-.75.75");
}

</style>
