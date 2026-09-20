<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmjp8pa6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-sliding-outline-sharp" /></template>
<style>
.qmjp8pa6t {
  fill: currentColor;
  d: path("M8.288 12.713Q8 12.425 8 12t.288-.712T9 11t.713.288T10 12t-.288.713T9 13t-.712-.288m6 0Q14 12.426 14 12t.288-.712T15 11t.713.288T16 12t-.288.713T15 13t-.712-.288M3 21v-2h1V3h16v16h1v2zm3-2h5V5H6zm7 0h5V5h-5zm-1-8");
}

</style>
