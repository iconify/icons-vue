<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8npo8bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-check-outline-rounded" /></template>
<style>
.l8npo8bqq {
  fill: currentColor;
  d: path("M6.808 20v-3q0-1.852 1.135-3.285T10.853 12q-1.774-.3-2.91-1.724T6.808 7V4H5.5q-.213 0-.357-.143T5 3.5t.143-.357T5.5 3h13q.214 0 .357.143T19 3.5t-.143.357T18.5 4h-1.308v3q0 1.777-1.075 3.146t-2.746 1.675q.289.02.76.145t.99.451q-.373.154-.679.34t-.576.445q-.404-.223-.882-.347T12 12.73q-1.765 0-2.979 1.252Q7.808 15.235 7.808 17v3h4.108q.078.28.19.521q.113.24.246.479H5.5q-.213 0-.357-.143T5 20.5t.143-.357T5.5 20zm8.17-9.983Q16.193 8.765 16.193 7V4H7.808v3q0 1.766 1.213 3.017Q10.234 11.27 12 11.27t2.979-1.252m.186 10.876Q14 19.73 14 18.058t1.165-2.836T18 14.058t2.836 1.164T22 18.058q0 1.67-1.164 2.835Q19.67 22.058 18 22.058t-2.835-1.165m2.135-1.931l-1.121-1.121q-.112-.112-.27-.122q-.157-.01-.288.122q-.13.13-.13.278t.13.279l1.114 1.114q.242.242.565.242t.566-.243l2.513-2.513q.111-.112.121-.27q.01-.157-.121-.288t-.279-.13t-.279.13z");
}

</style>
