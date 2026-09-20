<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utt6s6bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-pause-outline" /></template>
<style>
.utt6s6bul {
  fill: currentColor;
  d: path("M5 21v-1h1.808v-3q0-1.852 1.135-3.285T10.853 12q-1.774-.3-2.91-1.724T6.808 7V4H5V3h14v1h-1.808v3q0 1.777-1.075 3.146t-2.746 1.675q.289.02.76.145t.99.451q-.373.154-.679.34t-.576.445q-.404-.223-.882-.347T12 12.73q-1.765 0-2.979 1.252Q7.808 15.235 7.808 17v3h4.108q.078.28.19.521q.113.24.246.479zm9.979-10.983Q16.192 8.765 16.192 7V4H7.808v3q0 1.766 1.213 3.017Q10.234 11.27 12 11.27t2.979-1.252m3.694 9.733h.77v-3.384h-.77zm-2.115 0h.769v-3.384h-.77zm-1.394 1.143Q14 19.73 14 18.058t1.165-2.836T18 14.058t2.836 1.164T22 18.058q0 1.67-1.164 2.835Q19.67 22.058 18 22.058t-2.835-1.165M12 4");
}

</style>
