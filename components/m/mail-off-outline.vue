<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4xbz92_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-off-outline" /></template>
<style>
.j4xbz92_c {
  fill: currentColor;
  d: path("M19.775 22.625L17.15 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4l2 2H4v12h11.15L1.375 4.225L2.8 2.8l18.4 18.4zm2-3.7L20 17.15V8l-5.625 3.525L13.15 10.3L20 6H8.85l-2-2H20q.825 0 1.413.588T22 6v12q0 .25-.05.488t-.175.437");
}

</style>
