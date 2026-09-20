<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sktekx1lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-text-overflow-rounded" /></template>
<style>
.sktekx1lp {
  fill: currentColor;
  d: path("M4.288 19.713Q4 19.425 4 19V5q0-.425.288-.712T5 4t.713.288T6 5v14q0 .425-.288.713T5 20t-.712-.288m8-11Q12 8.425 12 8V5q0-.425.288-.712T13 4t.713.288T14 5v3q0 .425-.288.713T13 9t-.712-.288m4.887 6.113q-.3.3-.712.3t-.713-.3t-.3-.7t.3-.7l.425-.425H9q-.425 0-.712-.288T8 12t.288-.712T9 11h7.175l-.425-.425q-.3-.3-.3-.7t.3-.7t.713-.3t.712.3L19.3 11.3q.3.3.3.7t-.3.7zm-4.887 4.888Q12 19.425 12 19v-3q0-.425.288-.712T13 15t.713.288T14 16v3q0 .425-.288.713T13 20t-.712-.288");
}

</style>
