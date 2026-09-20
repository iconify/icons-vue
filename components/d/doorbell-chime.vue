<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hex7nm1uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:doorbell-chime" /></template>
<style>
.hex7nm1uv {
  fill: currentColor;
  d: path("m21.704 16.354l-.708-.708q.727-.727 1.116-1.676T22.5 12t-.388-1.97t-1.096-1.676l.688-.708q.873.873 1.334 1.996q.462 1.124.462 2.358t-.461 2.358q-.462 1.123-1.335 1.996m-2.675-2l-.733-.708q.333-.333.518-.754Q19 12.472 19 12t-.185-.892q-.186-.422-.519-.754l.733-.708q.473.473.722 1.074T20 12t-.249 1.28t-.722 1.074m-10.21 5.828Q7.5 18.863 7.5 17V7q0-1.864 1.318-3.182T12 2.5t3.182 1.318T16.5 7v10q0 1.864-1.318 3.182T12 21.5t-3.182-1.318m4.517-2.846q.55-.55.55-1.336t-.55-1.336T12 14.117t-1.336.549T10.117 16t.549 1.336t1.335.549t1.336-.55m-2.126-.546q-.326-.326-.326-.789t.326-.79t.79-.325t.79.326t.326.789t-.326.79t-.79.326t-.79-.326m2.125-7.454q.55-.55.55-1.336t-.55-1.336T12 6.117t-1.336.549T10.117 8t.549 1.336T12 9.885t1.336-.55");
}

</style>
