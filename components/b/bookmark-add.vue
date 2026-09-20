<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw_zaw63d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-add" /></template>
<style>
.bw_zaw63d {
  fill: currentColor;
  d: path("M6 19.5V5.616q0-.691.463-1.153T7.616 4h6.153q-.384.596-.577 1.197T13 6.5q0 1.742 1.157 3.012T17 10.958q.287.036.5.036t.5-.036V19.5l-6-2.577zM17 9V7h-2V6h2V4h1v2h2v1h-2v2z");
}

</style>
