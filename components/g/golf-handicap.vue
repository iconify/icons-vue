<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl4trkbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-handicap" /></template>
<style>
.vl4trkbyg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 3.75h-11q-1.76 0-3.005 1.245T2.25 8v8q0 1.76 1.245 3.005T6.5 20.25h11q1.76 0 3.005-1.245T21.75 16V8q0-1.76-1.245-3.005T17.5 3.75M15 7.25q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .196-.096.368l-4.5 8q-.073.13-.191.222q-.117.092-.261.132q-.143.04-.292.023q-.148-.018-.278-.091t-.222-.191t-.132-.261t-.023-.292t.091-.278l3.872-6.882H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 8t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 7.25z");
}

</style>
