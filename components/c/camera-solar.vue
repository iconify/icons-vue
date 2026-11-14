<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgyxlacke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-solar" /></template>
<style>
.wgyxlacke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 2.25h3.25q-.15 0-.288.058q-.138.057-.243.163q-.106.105-.163.243q-.056.138-.056.288t.058.286l2.5 6q.028.069.069.13t.094.113t.114.093t.129.07q.069.028.141.042q.073.014.147.014q.073 0 .146-.015q.072-.014.14-.043t.13-.069t.113-.094q.053-.052.093-.114q.041-.061.07-.129q.028-.069.042-.141q.014-.073.014-.147q0-.073-.015-.146q-.014-.072-.043-.14l-2.5-6q-.042-.103-.113-.189q-.071-.085-.163-.147t-.199-.094t-.217-.032H17q1.5 0 2.077 1.384l1.25 3.001q.464 1.111-.205 2.113q-.668 1.002-1.872 1.002h-2v1.5H17q2.75 0 2.75 2.75v5.5q0 2.75-2.75 2.75H7q-2.75 0-2.75-2.75V14q0-2.75 2.75-2.75h7.75v-1.5H8.5q-1.5 0-2.077-1.385l-1.25-3q-.464-1.111.205-2.113Q6.046 2.25 7.25 2.25m2 14.5q0 2.75 2.75 2.75t2.75-2.75T12 14t-2.75 2.75");
}

</style>
