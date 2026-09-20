<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmhxdvbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-3-2" /></template>
<style>
.wmhxdvbxs {
  fill: currentColor;
  d: path("M5 18q-.825 0-1.412-.587T3 16V8q0-.825.588-1.412T5 6h14q.825 0 1.413.588T21 8v8q0 .825-.587 1.413T19 18z");
}

</style>
