<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgztz8boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drone-sharp" /></template>
<style>
.sgztz8boo {
  fill: currentColor;
  d: path("M4 20q0-1.875 1.025-3.363t2.65-2.162L7.425 12H4V6H1V4h8v2H6v4h1.2L7 8h10l-.2 2H18V6h-3V4h8.025v2h-3v6H16.6l-.25 2.475q1.625.675 2.638 2.163T20 20h-2q0-1.65-1.175-2.825T14 16h-4q-1.65 0-2.825 1.175T6 20z");
}

</style>
