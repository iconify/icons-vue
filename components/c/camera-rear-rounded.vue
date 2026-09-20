<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpqig7bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-rear-rounded" /></template>
<style>
.bpqig7bol {
  fill: currentColor;
  d: path("M12.578 7.078q.23-.23.23-.54T12.578 6t-.54-.23T11.5 6t-.23.54q0 .309.23.539t.54.23t.539-.23M6 4.615q0-.67.472-1.143Q6.944 3 7.616 3h8.769q.67 0 1.143.472q.472.472.472 1.144V7.83q.373.04.648.31q.275.268.275.647v1.77q0 .378-.275.648t-.648.31v4.676q0 .349-.23.578t-.578.23h-3.938q-.323 0-.628-.13t-.522-.349l-.623-.623q-.242-.242-.538-.351q-.295-.108-.593-.108t-.596.108t-.54.351l-.623.623q-.218.217-.523.348T7.441 17h-.633q-.348 0-.578-.23T6 16.192zM11.242 19.5H6.5q-.213 0-.357-.143T6 19t.143-.357t.357-.143h4.742l-1.246-1.246q-.14-.14-.15-.345q-.01-.203.15-.363t.354-.16t.354.16l1.888 1.889q.131.13.184.267q.053.136.053.298t-.053.298t-.184.267l-1.888 1.889q-.14.14-.345.15q-.203.01-.363-.15t-.16-.354t.16-.354zm3.258 0q-.213 0-.357-.143T14 19t.143-.357t.357-.143h3q.214 0 .357.143T18 19t-.143.357t-.357.143z");
}

</style>
