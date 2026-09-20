<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wb-4_w0uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-closed-alert-20-filled" /></template>
<style>
.wb-4_w0uk {
  fill: currentColor;
  d: path("M10.5 5a3 3 0 0 1 6 0v2l1.32 1.119a.5.5 0 0 1-.324.881H9.503a.5.5 0 0 1-.323-.881L10.5 7zm3 6a1.5 1.5 0 0 1-1.415-1h2.829a1.5 1.5 0 0 1-1.415 1m-4-4.463l-.967.819C7.468 8.259 8.106 10 9.503 10h1.52l.119.334A2.5 2.5 0 0 0 14 11.95V15a2 2 0 0 1-2 2H6a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h3.5z");
}

</style>
