<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4_tgob1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:finds-bag" /></template>
<style>
.o4_tgob1k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 6.483q.007-3.733 3-3.733q3 0 3 3.75t-3 3.75q-2.309 0-2.841-2.222L13.501 9.04q3.488 1.98 3.81 6.911q.163 2.504-.877 4.259q-1.208 2.04-3.434 2.04H8q-2.226 0-3.434-2.04q-1.04-1.755-.877-4.259q.362-5.544 4.727-7.358L6.344 4.864q-.072-.13-.089-.278t.024-.292q.041-.143.134-.26q.092-.117.223-.19q.17-.094.364-.094h7q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .194-.094.364l-1.502 2.703zM11.059 8.25l1.666-3h-4.45l1.666 3z");
}

</style>
