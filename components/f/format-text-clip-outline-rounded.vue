<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfvy-y8qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-text-clip-outline-rounded" /></template>
<style>
.sfvy-y8qw {
  fill: currentColor;
  d: path("M4.288 19.713Q4 19.425 4 19V5q0-.425.288-.712T5 4t.713.288T6 5v14q0 .425-.288.713T5 20t-.712-.288m14 0Q18 19.426 18 19v-6H9q-.425 0-.712-.288T8 12t.288-.712T9 11h9V5q0-.425.288-.712T19 4t.713.288T20 5v14q0 .425-.288.713T19 20t-.712-.288");
}

</style>
