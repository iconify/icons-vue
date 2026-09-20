<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4lxygwpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess-rook-outline" /></template>
<style>
.m4lxygwpn {
  fill: currentColor;
  d: path("M4 22v-5q2.025-1.625 3.05-3.525T8.5 10H8q-.825 0-1.412-.587T6 8V2h5v3h2V2h5v6q0 .825-.587 1.413T16 10h-.525q.425 1.575 1.45 3.475T20 17v5zm2-2h12v-2.075q-2.15-1.95-3.162-4.088T13.4 10h-2.825q-.4 1.7-1.425 3.838T6 17.925zM8 8h8V4h-1v3H9V4H8zm0 0h8z");
}

</style>
