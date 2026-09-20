<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdbs5zbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-clock-outline-rounded" /></template>
<style>
.jdbs5zbur {
  fill: currentColor;
  d: path("M9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zM6.616 21q-.691 0-1.153-.462T5 19.385v-8.77q0-.69.463-1.152T6.616 9H8V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h1.385q.69 0 1.152.463T19 10.616v.461q0 .25-.159.375q-.158.125-.341.125t-.341-.125t-.159-.375v-.461q0-.27-.173-.443T17.384 10H6.616q-.27 0-.443.173T6 10.616v8.769q0 .269.173.442t.443.173h5.519q.213 0 .356.143t.144.357t-.144.357t-.356.143zm8.164-.549q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165M18 17.454v-2.339q0-.161-.111-.273t-.273-.111t-.274.111t-.111.273v2.333q0 .162.055.301t.187.27l1.52 1.52q.11.111.263.12q.152.01.282-.12t.131-.274t-.13-.273zM6 15.769V20V10z");
}

</style>
