<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<g class="cuyn6tgcc"><path class="nbzw50bsa"/><path class="w_z-bobvy"/><path class="rb8v0tbpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-28-regular" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nbzw50bsa {
  d: path("M27 20.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0m-6.5-4a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H21v-3a.5.5 0 0 0-.5-.5");
}

.rb8v0tbpd {
  d: path("M16.25 12.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5z");
}

.w_z-bobvy {
  d: path("M22.75 3A2.25 2.25 0 0 1 25 5.25v2c0 .78-.397 1.467-1 1.871v4.745a7.5 7.5 0 0 0-1.5-.594V9.5h-17v10.75a3.25 3.25 0 0 0 3.25 3.25h4.876A7.5 7.5 0 0 0 14.5 25H8.75A4.75 4.75 0 0 1 4 20.25V9.121A2.25 2.25 0 0 1 3 7.25v-2A2.25 2.25 0 0 1 5.25 3zM5.25 4.5a.75.75 0 0 0-.75.75v2c0 .414.336.75.75.75h17.5a.75.75 0 0 0 .75-.75v-2a.75.75 0 0 0-.75-.75z");
}

</style>
