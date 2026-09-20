<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s91i1dmrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-break-right-outline-rounded" /></template>
<style>
.s91i1dmrq {
  fill: currentColor;
  d: path("M11 16V8q0-.425.288-.712T12 7h8q.425 0 .713.288T21 8v8q0 .425-.288.713T20 17h-8q-.425 0-.712-.288T11 16m2-1h6V9h-6zm-9 6q-.425 0-.712-.288T3 20t.288-.712T4 19h16q.425 0 .713.288T21 20t-.288.713T20 21zM4 5q-.425 0-.712-.288T3 4t.288-.712T4 3h16q.425 0 .713.288T21 4t-.288.713T20 5z");
}

</style>
