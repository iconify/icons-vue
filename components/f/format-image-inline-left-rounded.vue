<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqykl1bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-inline-left-rounded" /></template>
<style>
.oqykl1bnv {
  fill: currentColor;
  d: path("M3 16V8q0-.425.288-.712T4 7h8q.425 0 .713.288T13 8v8q0 .425-.288.713T12 17H4q-.425 0-.712-.288T3 16m13 1q-.425 0-.712-.288T15 16t.288-.712T16 15h4q.425 0 .713.288T21 16t-.288.713T20 17zM4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h16q.425 0 .713.288T21 20t-.288.713T20 21zM4 5q-.425 0-.712-.288T3 4t.288-.712T4 3h16q.425 0 .713.288T21 4t-.288.713T20 5z");
}

</style>
