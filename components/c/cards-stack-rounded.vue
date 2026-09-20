<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfv746b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cards-stack-rounded" /></template>
<style>
.zfv746b8q {
  fill: currentColor;
  d: path("M10.808 8.5h6q.212 0 .356-.144t.144-.357t-.144-.356t-.356-.143h-6.006q-.215 0-.355.144t-.14.357t.144.356t.357.143m0 3.154h3q.212 0 .356-.144t.144-.357t-.144-.356t-.356-.143h-3.006q-.215 0-.355.144t-.14.357t.144.356t.357.143m-4.973 8.302q-.652.086-1.164-.313q-.511-.4-.613-1.06L2.87 10.177q-.067-.416.202-.759t.69-.408h.449v5.317q0 1.332.949 2.282q.949.949 2.281.949H18.98q-.085.332-.344.56t-.608.284zm2.396-4.76q-.69 0-1.153-.462t-.462-1.153V5.616q0-.691.462-1.153T8.231 4h11.154q.69 0 1.153.463T21 5.616v7.965q0 .69-.462 1.153t-1.153.462z");
}

</style>
