<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwn1e8b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-left-20-filled" /></template>
<style>
.vwn1e8b6p {
  fill: currentColor;
  d: path("M14.95 13.955a7.005 7.005 0 0 0 0-9.904a7 7 0 0 0-9.9 0a7.005 7.005 0 0 0 0 9.904l1.521 1.499l2.043 1.985l.133.118c.775.628 1.91.588 2.64-.118l2.435-2.37zM9.854 6.354L8.207 8H13a.5.5 0 0 1 0 1H8.207l1.647 1.646a.5.5 0 0 1-.708.708l-2.5-2.5a.5.5 0 0 1 0-.708l2.5-2.5a.5.5 0 1 1 .708.708");
}

</style>
