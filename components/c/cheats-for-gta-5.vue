<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qswav5bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cheats-for-gta-5" /></template>
<style>
.qswav5bho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.55 15.72l.006-10.214L18.45 5.5l-.006 10.3l5.581 5.48zm2.73 13.83l10.214.006l.006-11.106l-10.299-.006l-5.48 5.581zm-13.83 2.73l-.006 10.214l11.107.006l.005-10.299l-5.581-5.48zm-2.73-13.83l-10.214-.006L5.5 29.55l10.299.005l5.48-5.581z");
}

</style>
