<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-3lc-b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-plus-outline-rounded" /></template>
<style>
.v-3lc-b5j {
  fill: currentColor;
  d: path("M16 19h-2q-.425 0-.712-.288T13 18t.288-.712T14 17h2v-2q0-.425.288-.712T17 14t.713.288T18 15v2h2q.425 0 .713.288T21 18t-.288.713T20 19h-2v2q0 .425-.288.713T17 22t-.712-.288T16 21zm-8 3q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V3q0-.425.288-.712T11 2h2q.425 0 .713.288T14 3v1h2q.425 0 .713.288T17 5v6q0 .425-.288.713T16 12t-.712-.288T15 11V6H9v14h2.525q.425 0 .713.288t.287.712t-.288.713t-.712.287z");
}

</style>
