<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g55ca7buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fork-spoon-rounded" /></template>
<style>
.g55ca7buv {
  fill: currentColor;
  d: path("M6.288 21.713Q6 21.425 6 21v-8.15q-1.35-.35-2.175-1.425T3 9V3q0-.425.288-.712T4 2t.713.288T5 3v5h1V3q0-.425.288-.712T7 2t.713.288T8 3v5h1V3q0-.425.288-.712T10 2t.713.288T11 3v6q0 1.35-.825 2.425T8 12.85V21q0 .425-.288.713T7 22t-.712-.288m10 0Q16 21.426 16 21v-8.525q-1.35-.45-2.175-1.887T13 7.325Q13 5.1 14.175 3.55T17 2t2.825 1.562T21 7.35q0 1.825-.825 3.25T18 12.475V21q0 .425-.288.713T17 22t-.712-.288");
}

</style>
