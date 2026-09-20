<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txa294b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hourglass-pause-sharp" /></template>
<style>
.txa294b4g {
  fill: currentColor;
  d: path("M5 21v-1h1.808v-3q0-1.852 1.135-3.285T10.853 12q-1.774-.3-2.91-1.724T6.808 7V4H5V3h14v1h-1.808v3q0 1.777-1.075 3.146t-2.746 1.675q.018.089.267.36q.249.273.606.808q-1.238.842-1.933 2.182t-.695 2.887q0 .786.19 1.523T12.352 21zm10.165-.107Q14 19.73 14 18.058t1.165-2.836T18 14.058t2.836 1.164T22 18.058q0 1.67-1.164 2.835Q19.67 22.058 18 22.058t-2.835-1.165m1.393-1.143h.769v-3.384h-.77zm2.115 0h.77v-3.384h-.77z");
}

</style>
