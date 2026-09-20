<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8co04bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hd-outline" /></template>
<style>
.p8co04bhv {
  fill: currentColor;
  d: path("M6 15h1.5v-2h2v2H11V9H9.5v2.5h-2V9H6zm7 0h4q.425 0 .713-.288T18 14v-4q0-.425-.288-.712T17 9h-4zm1.5-1.5v-3h2v3zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zm0 0V6z");
}

</style>
