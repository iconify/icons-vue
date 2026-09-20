<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l46o2bsjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-off-24-filled" /></template>
<style>
.l46o2bsjt {
  fill: currentColor;
  d: path("m2.5 2.5l18 18a.75.75 0 0 1-1.06 1.062L14.377 16.5H4.5v4.75a.75.75 0 0 1-.648.744L3.75 22a.75.75 0 0 1-.743-.648L3 21.25V5.122l-1.56-1.56A.75.75 0 1 1 2.5 2.5m2.617.498h15.137a.75.75 0 0 1 .6 1.2L16.69 9.75l4.164 5.55a.75.75 0 0 1-.6 1.2h-1.633z");
}

</style>
