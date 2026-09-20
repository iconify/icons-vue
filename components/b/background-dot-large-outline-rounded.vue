<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0mj3acif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:background-dot-large-outline-rounded" /></template>
<style>
.o0mj3acif {
  fill: currentColor;
  d: path("M9.736 15.582q.264-.265.264-.659t-.264-.659T9.077 14t-.659.265t-.264.658t.264.659t.659.264t.659-.264m0-5.847Q10 9.471 10 9.077t-.264-.659t-.659-.264t-.659.264t-.264.659t.264.659q.265.264.659.264t.659-.264m5.846 5.846q.264-.265.264-.659t-.264-.659t-.659-.264t-.659.265t-.264.658t.265.659t.658.264t.659-.264m0-5.847q.264-.264.264-.658t-.264-.659t-.659-.264t-.659.264t-.264.659t.265.659t.658.264t.659-.264M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14z");
}

</style>
