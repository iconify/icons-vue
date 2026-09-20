<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd27t05gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:casino-rounded" /></template>
<style>
.cd27t05gm {
  fill: currentColor;
  d: path("M8.736 16.582Q9 16.317 9 15.923t-.264-.659t-.66-.264t-.659.265q-.264.264-.264.658t.264.659t.659.264t.659-.264m0-7.847Q9 8.471 9 8.077t-.264-.659t-.659-.264t-.659.264t-.264.659t.264.659t.659.264t.659-.264m3.923 3.923q.264-.265.264-.659t-.264-.659q-.265-.264-.659-.264t-.659.264q-.264.265-.264.659t.264.659q.265.264.659.264t.659-.264m3.923 3.923q.264-.265.264-.659t-.264-.659t-.659-.264t-.659.265t-.264.658t.265.659t.658.264t.659-.264m0-7.847q.264-.264.264-.658t-.264-.659t-.659-.264t-.659.264t-.264.659t.265.659t.658.264t.659-.264M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
