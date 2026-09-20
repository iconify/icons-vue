<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5p8dokdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-bus-outline" /></template>
<style>
.p5p8dokdl {
  fill: currentColor;
  d: path("M6 21q-.425 0-.712-.288T5 20v-2.05q-.45-.5-.725-1.112T4 15.5V6q0-2.075 1.925-3.037T12 2q4.3 0 6.15.925T20 6v9.5q0 .725-.275 1.338T19 17.95V20q0 .425-.288.713T18 21h-1q-.425 0-.712-.288T16 20v-1H8v1q0 .425-.288.713T7 21zm6.05-16h5.6h-11.2zM16 12H6h12zM6 10h12V7H6zm3.563 5.563Q10 15.125 10 14.5t-.437-1.062T8.5 13t-1.062.438T7 14.5t.438 1.063T8.5 16t1.063-.437m7 0Q17 15.125 17 14.5t-.437-1.062T15.5 13t-1.062.438T14 14.5t.438 1.063T15.5 16t1.063-.437M6.45 5h11.2q-.375-.425-1.612-.712T12.05 4q-2.675 0-3.912.313T6.45 5M8 17h8q.825 0 1.413-.587T18 15v-3H6v3q0 .825.588 1.413T8 17");
}

</style>
