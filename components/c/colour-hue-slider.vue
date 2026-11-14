<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk7-hpb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-hue-slider" /></template>
<style>
.tk7-hpb5d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.788 8.288Q1.25 9.825 1.25 12t1.538 3.712Q4.325 17.25 6.5 17.25t3.712-1.538q1.266-1.265 1.49-2.962h3.048V14q0 .932.659 1.591T17 16.25t1.591-.659T19.25 14v-1.25h2.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.25V10q0-2.25-2.25-2.25T14.75 10v1.25h-3.048q-.224-1.697-1.49-2.962Q8.675 6.75 6.5 6.75T2.788 8.288");
}

</style>
