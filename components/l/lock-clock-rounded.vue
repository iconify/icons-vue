<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2iqvtbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-clock-rounded" /></template>
<style>
.m2iqvtbva {
  fill: currentColor;
  d: path("M9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zM6.616 21q-.672 0-1.144-.472T5 19.385v-8.77q0-.67.472-1.143Q5.944 9 6.616 9H8V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h1.385q.67 0 1.143.472q.472.472.472 1.144v.284q0 .348-.27.566t-.624.18q-.123-.006-.252-.009l-.258-.002q-2.482 0-4.231 1.749q-1.75 1.749-1.75 4.232q0 .628.124 1.245q.124.616.38 1.189q.142.329-.028.64q-.17.31-.518.31zm8.164-.549q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165M18 17.454v-2.339q0-.161-.111-.273t-.273-.111t-.274.111t-.111.273v2.333q0 .162.055.301t.187.27l1.52 1.52q.11.111.263.12q.152.01.282-.12t.131-.274t-.13-.273z");
}

</style>
