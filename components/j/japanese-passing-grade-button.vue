<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hd6t3iykl"/><g class="n1mjunbsu"><path class="frebwobeo"/><path class="ed0csmbqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:japanese-passing-grade-button" /></template>
<style>
.ed0csmbqe {
  d: path("M20.9 29.5h22.3v5.1H20.9zM16 36.8V52h32V36.8zm25.6 9.8H22.4v-4.3h19.1z");
}

.frebwobeo {
  d: path("M32 12S22 20.6 9.8 26.6l3.2 6.1s7.9-2.6 19-11.5c11.1 8.9 19 11.5 19 11.5l3.2-6.1C42 20.6 32 12 32 12");
}

.hd6t3iykl {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("M62 52c0 5.5-4.5 10-10 10H12C6.5 62 2 57.5 2 52V12C2 6.5 6.5 2 12 2h40c5.5 0 10 4.5 10 10z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

</style>
