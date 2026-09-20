<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmhvmcttn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-reset-outline-rounded" /></template>
<style>
.rmhvmcttn {
  fill: currentColor;
  d: path("M20.291 15.507q-.708 1.643-1.923 2.859t-2.858 1.925T12 21q-1.784 0-3.363-.646t-2.79-1.786t-1.966-2.675t-.864-3.32q-.011-.244.13-.372q.14-.128.322-.14t.36.096t.188.382q.202 3.178 2.503 5.332T12 20.025q3.35 0 5.675-2.325T20 12.025T17.675 6.35T12 4.025q-2.436 0-4.365 1.28q-1.927 1.28-2.881 3.349h2.4q.212 0 .356.144t.144.357t-.144.356t-.356.143h-3.34q-.354 0-.584-.232T3 8.846V5.5q0-.213.144-.356T3.501 5t.356.144T4 5.5v2.48q1.087-2.228 3.21-3.604T12 3q1.868 0 3.51.709t2.858 1.922t1.923 2.857t.709 3.509t-.709 3.51M10 15.769q-.376 0-.63-.254q-.254-.255-.254-.63v-3q0-.376.287-.63q.287-.255.712-.255V9.884q0-.777.55-1.33Q11.213 8 12 8t1.336.554t.548 1.33V11q.426 0 .713.254q.288.255.288.63v3q0 .377-.255.631q-.254.254-.63.254zM10.885 11h2.23V9.892q0-.47-.325-.797T12 8.77t-.79.326t-.326.797z");
}

</style>
