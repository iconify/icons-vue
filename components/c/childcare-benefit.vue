<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyj5kabuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:childcare-benefit" /></template>
<style>
.vyj5kabuw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.75q3.402 0 5.815 2.252Q20.25 7.275 20.25 10.5q0 2.658-2.503 4.494Q15.352 16.75 12 16.75t-5.747-1.756q-2.428-1.781-2.501-4.335L2.311 7.295q-.029-.067-.045-.14q-.015-.072-.016-.146t.013-.146q.013-.073.041-.142q.027-.068.067-.13t.092-.115t.113-.094t.129-.071q.137-.059.286-.061t.288.054q.138.055.245.159t.165.242L4.995 9.75h6.255v.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.75 12 2.75M8 17.5q-2.25 0-2.25 2.25T8 22t2.25-2.25T8 17.5m5.75 2.25q0-2.25 2.25-2.25t2.25 2.25T16 22t-2.25-2.25");
}

</style>
