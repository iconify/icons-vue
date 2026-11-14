<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk34ngbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loading-circle" /></template>
<style>
.vk34ngbou {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-1.75 0-1.75 1.75T12 5.25t1.75-1.75T12 1.75M4.25 6q0-1.75 1.75-1.75T7.75 6T6 7.75T4.25 6m12 0q0-1.75 1.75-1.75T19.75 6T18 7.75T16.25 6M3.5 10.25q-1.75 0-1.75 1.75t1.75 1.75T5.25 12T3.5 10.25m17 0q-1.75 0-1.75 1.75t1.75 1.75T22.25 12t-1.75-1.75M4.25 18q0-1.75 1.75-1.75T7.75 18T6 19.75T4.25 18m12 0q0-1.75 1.75-1.75T19.75 18T18 19.75T16.25 18m-4.25.75q-1.75 0-1.75 1.75T12 22.25t1.75-1.75T12 18.75");
}

</style>
