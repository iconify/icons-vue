<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hms8s3b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-horiz-000-outline-rounded" /></template>
<style>
.hms8s3b1w {
  fill: currentColor;
  d: path("M5 17q-.425 0-.712-.288T4 16v-2H3q-.425 0-.712-.288T2 13v-2q0-.425.288-.712T3 10h1V8q0-.425.288-.712T5 7h16q.425 0 .713.288T22 8v8q0 .425-.288.713T21 17zm1-2h14V9H6z");
}

</style>
