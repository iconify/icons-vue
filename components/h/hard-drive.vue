<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i37j08p9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hard-drive" /></template>
<style>
.i37j08p9x {
  fill: currentColor;
  d: path("M17 16q.625 0 1.063-.425T18.5 14.5q0-.625-.437-1.062T17 13q-.65 0-1.075.438T15.5 14.5q0 .65.425 1.075T17 16M2 9l3.4-3.4q.275-.275.638-.437T6.825 5H17.15q.425 0 .788.163t.637.437L22 9zm2 10q-.85 0-1.425-.575T2 17v-6h20v6q0 .85-.587 1.425T20 19z");
}

</style>
