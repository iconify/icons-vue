<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtdwusbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collections-bookmark-outline-rounded" /></template>
<style>
.dtdwusbfg {
  fill: currentColor;
  d: path("M8 16h12V4h-2v6.125q0 .3-.25.45t-.5-.025l-1.225-.725q-.25-.15-.537-.15t-.513.15l-1.225.725q-.275.175-.513.025t-.237-.45V4H8zm0 2q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm-4 4q-.825 0-1.412-.587T2 20V7q0-.425.288-.712T3 6t.713.288T4 7v13h13q.425 0 .713.288T18 21t-.288.713T17 22zM8 4v12zm5 6.125q0 .3.238.45t.512-.025l1.225-.725q.225-.15.513-.15t.537.15l1.225.725q.25.175.5.025t.25-.45q0 .3-.25.45t-.5-.025l-1.225-.725q-.25-.15-.537-.15t-.513.15l-1.225.725q-.275.175-.513.025t-.237-.45");
}

</style>
