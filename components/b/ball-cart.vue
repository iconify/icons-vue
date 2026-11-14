<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4tszxb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-cart" /></template>
<style>
.e4tszxb9b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.819 6.75h-1.611q-.354-3-3.708-3q-1.553 0-2.652 1.098q-.823.823-1.029 1.902H3.5q-.087 0-.172.02q-.072.017-.139.047q-.067.031-.127.074t-.11.097t-.09.117t-.064.132t-.038.142t-.01.147t.02.146l2 8.5q.056.237.24.396q-.26.586-.26 1.432q0 2.75 2.75 2.75T10.25 18q0-.719-.188-1.25h3.876q-.188.531-.188 1.25q0 2.75 2.75 2.75T19.25 18q0-.846-.26-1.432q.184-.159.24-.396l2-8.5q.02-.085.02-.172q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-.292q-.354-3-3.708-3q-1.553 0-2.652 1.098q-.823.823-1.029 1.902m1.507 0h4.348q-.337-1.5-2.174-1.5t-2.174 1.5M7.5 5.25q1.837 0 2.174 1.5H5.326q.337-1.5 2.174-1.5");
}

</style>
