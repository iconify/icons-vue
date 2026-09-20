<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlm4j-ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ev-station-sharp" /></template>
<style>
.vlm4j-ble {
  fill: currentColor;
  d: path("M6 10.5h6V5H6zM5 20V4h8v7.616h2.539v7.5h2.865V8.885H17.25V6.5h.404V5.385h.769V6.5h.846V5.385h.77V6.5h.403v2.385h-1.154V20h-4.634v-7.5H13V20zm3.654-1.884l1.769-3.231H9.366v-2.52l-1.789 3.231h1.077z");
}

</style>
