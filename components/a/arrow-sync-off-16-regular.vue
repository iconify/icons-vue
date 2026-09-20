<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v3_jc_e7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sync-off-16-regular" /></template>
<style>
.v3_jc_e7x {
  fill: currentColor;
  d: path("M3.418 4.126A5.98 5.98 0 0 0 2 8a5.99 5.99 0 0 0 2.222 4.661a.5.5 0 0 0 .63-.776A4.99 4.99 0 0 1 3 8c0-1.2.423-2.302 1.129-3.164l7.035 7.035a4.98 4.98 0 0 1-2.953 1.125l.643-.642a.5.5 0 0 0-.708-.708l-1.5 1.5a.5.5 0 0 0 0 .708l1.5 1.5a.5.5 0 0 0 .708-.708l-.65-.65a5.97 5.97 0 0 0 3.67-1.415l2.272 2.273a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708zm9.016 6.187l.735.735A5.97 5.97 0 0 0 14 8a5.99 5.99 0 0 0-2.222-4.661a.5.5 0 1 0-.63.776A4.99 4.99 0 0 1 13 8c0 .834-.204 1.621-.566 2.313M4.952 2.83l.735.735a5 5 0 0 1 2.101-.562l-.642.642a.5.5 0 1 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708l-1.5-1.5a.5.5 0 1 0-.708.708l.65.65a6 6 0 0 0-2.844.827");
}

</style>
