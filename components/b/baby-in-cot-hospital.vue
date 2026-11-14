<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u85gyab8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-in-cot-hospital" /></template>
<style>
.u85gyab8h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 3.75h11q1.76 0 3.005 1.245T21.75 8v1q0 1.76-1.245 3.005T17.5 13.25h-.757l-3.462 2.5l3.658 2.642q.066.048.12.108q1.941.03 1.941 2q0 2-2 2t-2-2q0-.883.39-1.376L12 16.675l-3.39 2.449Q9 19.617 9 20.5q0 2-2 2t-2-2q0-1.97 1.941-2q.054-.06.12-.108l3.658-2.642l-3.462-2.5H6.5q-1.76 0-3.005-1.245T2.25 9V8q0-1.76 1.245-3.005T6.5 3.75M8 6Q5.5 6 5.5 8.5T8 11t2.5-2.5T8 6m9.5 1.75h-6q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M12 14.825l2.181-1.575H9.819z");
}

</style>
