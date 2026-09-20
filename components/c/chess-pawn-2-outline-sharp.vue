<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0uezcnxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-pawn-2-outline-sharp" /></template>
<style>
.s0uezcnxz {
  fill: currentColor;
  d: path("M5 21q.135-2.196 1.452-3.93q1.317-1.735 3.39-2.403q-.973-.552-1.523-1.514t-.55-2.095q0-1.312.72-2.375q.72-1.064 1.934-1.547q-.385-.336-.586-.79q-.202-.454-.202-.962q0-.985.689-1.675t1.673-.69t1.676.69t.693 1.675q0 .508-.202.962t-.587.79q1.214.483 1.934 1.547q.72 1.063.72 2.375q0 1.132-.553 2.095q-.553.962-1.526 1.514q2.073.667 3.393 2.402T19 21zm7-5.692q-2.117.019-3.744 1.33T6.152 20h11.69q-.476-2.05-2.1-3.362q-1.625-1.311-3.742-1.33m0-1q1.346 0 2.288-.95t.943-2.308t-.943-2.31T12 7.788t-2.289.954t-.942 2.316q0 1.354.942 2.302t2.289.948m.972-7.923q.394-.402.394-.981t-.393-.992T12.001 4t-.973.412q-.394.413-.394.992t.393.981t.972.403t.973-.403M12 11.04");
}

</style>
