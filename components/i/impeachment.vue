<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc5z5bcac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:impeachment" /></template>
<style>
.mc5z5bcac {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.846 7.205l3.359-3.359q2.386-2.386 4.772 0l.177.177q2.386 2.386 0 4.772l-1.149 1.149l5.025 5.026q.106.105.163.243t.057.287t-.057.287t-.163.243q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-5.026-5.025l-1.149 1.149q-2.386 2.386-4.772 0l-.177-.177q-2.386-2.386 0-4.772M20 17.75q2.25 0 2.25 2.25T20 22.25h-7q-2.25 0-2.25-2.25T13 17.75z");
}

</style>
