<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfy7pyfja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brain-fill-round" /></template>
<style>
.xfy7pyfja {
  fill: currentColor;
  d: path("M11 2.536v7.401a4 4 0 0 1-2.393 3.143a1 1 0 0 0 .786 1.84A6 6 0 0 0 11 13.91v7.092A5.002 5.002 0 0 1 2.999 17a5.006 5.006 0 0 1 .081-6.105a4.98 4.98 0 0 1 1.918-4.896A4.003 4.003 0 0 1 11 2.536m2 7.401V2.536a4 4 0 0 1 6.002 3.463a4.98 4.98 0 0 1 1.918 4.896A5.006 5.006 0 0 1 21.001 17A5 5 0 0 1 13 21.002V13.91a6 6 0 0 0 1.607 1.01a1 1 0 0 0 .786-1.84A4 4 0 0 1 13 9.937");
}

</style>
