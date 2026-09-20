<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0ygg2byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:discover-tune-rounded" /></template>
<style>
.x0ygg2byo {
  fill: currentColor;
  d: path("M14 9q-.425 0-.712-.288T13 8t.288-.712T14 7h2V4q0-.425.288-.712T17 3t.713.288T18 4v3h2q.425 0 .713.288T21 8t-.288.713T20 9zm2.288 11.713Q16 20.425 16 20v-8q0-.425.288-.712T17 11t.713.288T18 12v8q0 .425-.288.713T17 21t-.712-.288m-10 0Q6 20.426 6 20v-3H4q-.425 0-.712-.288T3 16t.288-.712T4 15h6q.425 0 .713.288T11 16t-.288.713T10 17H8v3q0 .425-.288.713T7 21t-.712-.288m0-8Q6 12.425 6 12V4q0-.425.288-.712T7 3t.713.288T8 4v8q0 .425-.288.713T7 13t-.712-.288");
}

</style>
