<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8v0_bbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-split-outline-rounded" /></template>
<style>
.d8v0_bbcx {
  fill: currentColor;
  d: path("M4 19q-.425 0-.712-.288T3 18v-4q0-.425.288-.712T4 13h16q.425 0 .713.288T21 14v4q0 .425-.288.713T20 19zm0-8q-.425 0-.712-.288T3 10t.288-.712T4 9h16q.425 0 .713.288T21 10t-.288.713T20 11zm0-4q-.425 0-.712-.288T3 6t.288-.712T4 5h16q.425 0 .713.288T21 6t-.288.713T20 7z");
}

</style>
