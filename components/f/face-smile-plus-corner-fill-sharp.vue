<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iigh_xbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-plus-corner-fill-sharp" /></template>
<style>
.iigh_xbpa {
  fill: currentColor;
  d: path("M21 2v1h1a1 1 0 0 1 0 2h-1v1a1 1 0 0 1-2 0V5h-1a1 1 0 0 1 0-2h1V2a1 1 0 0 1 2 0m-6.724.263a1 1 0 0 1 .765 1.101a4.9 4.9 0 0 0 .227 2.251a4.94 4.94 0 0 0 1.196 1.921a4.94 4.94 0 0 0 1.921 1.196c.722.25 1.493.326 2.251.227a1 1 0 0 1 1.101.765a10 10 0 0 1-3.297 9.926a9.98 9.98 0 0 1-10.333 1.564A10 10 0 0 1 2.493 8.899a9.987 9.987 0 0 1 11.783-6.636M9 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm6 2h.01a1 1 0 0 0 0-2H15a1 1 0 0 0 0 2m-6.293 3.293a.999.999 0 1 0-1.414 1.414a6.653 6.653 0 0 0 9.414 0a1.002 1.002 0 0 0-1.414-1.414a4.656 4.656 0 0 1-6.586 0");
}

</style>
