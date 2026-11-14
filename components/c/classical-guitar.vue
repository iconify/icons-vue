<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe-wligrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:classical-guitar" /></template>
<style>
.xe-wligrb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 3.75q0-2-2-2t-2 2v1q0 1.581 1.25 1.912v3.056q-.718.224-1.437.878q-1.89 1.719-.821 3.719q-1.195 1.037-1.442 2.691q-.306 2.04 1.041 3.603T12 22.172t3.409-1.563t1.041-3.603q-.247-1.654-1.442-2.691q1.069-2-.821-3.719q-.719-.654-1.437-.878V6.662Q14 6.331 14 4.75zm-4 14q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
