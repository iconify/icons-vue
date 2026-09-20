<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdb_zp12h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-check-rounded" /></template>
<style>
.qdb_zp12h {
  fill: currentColor;
  d: path("M5.5 21q-.213 0-.357-.143T5 20.5t.143-.357T5.5 20h1.308v-3q0-1.852 1.135-3.285T10.853 12q-1.774-.3-2.91-1.724T6.808 7V4H5.5q-.213 0-.357-.143T5 3.5t.143-.357T5.5 3h13q.214 0 .357.143T19 3.5t-.143.357T18.5 4h-1.308v3q0 1.777-1.075 3.146t-2.746 1.675q.018.089.267.36q.249.273.606.808q-1.238.842-1.933 2.182t-.695 2.887q0 .786.19 1.523T12.352 21zm9.665-.107Q14 19.73 14 18.058t1.165-2.836T18 14.058t2.836 1.164T22 18.058q0 1.67-1.164 2.835Q19.67 22.058 18 22.058t-2.835-1.165m2.135-1.931l-1.121-1.121q-.112-.112-.27-.122q-.157-.01-.288.122q-.13.13-.13.278t.13.279l1.114 1.114q.242.242.565.242t.566-.243l2.513-2.513q.111-.112.121-.27q.01-.157-.121-.288t-.279-.13t-.279.13z");
}

</style>
