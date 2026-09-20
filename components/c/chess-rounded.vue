<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q12j7az9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-rounded" /></template>
<style>
.q12j7az9w {
  fill: currentColor;
  d: path("M5.577 20.23q-.348 0-.578-.229t-.23-.578v-1.52q0-.67.472-1.142q.473-.472 1.144-.472h1.069l.685-4.789h-1.87q-.213 0-.356-.143T5.769 11t.144-.357t.356-.143h11.462q.213 0 .356.143t.144.357t-.144.357t-.356.143h-1.87l.685 4.789h1.07q.67 0 1.143.471q.472.473.472 1.144v1.519q0 .348-.23.578t-.578.23zm2.98-10.615q-.291 0-.509-.174q-.217-.174-.273-.466l-.844-3.783q-.05-.217.028-.372t.22-.28t.325-.147t.388.07q.335.135.675.198q.34.064.731.064q.648 0 1.212-.166q.563-.165 1.023-.461q.117-.067.23-.101q.114-.034.237-.034t.237.034q.113.034.23.101q.46.296 1.024.461q.563.166 1.192.166q.39 0 .72-.066q.332-.067.705-.22q.211-.068.4-.053t.333.141t.223.29t.03.375l-.863 3.802q-.056.293-.273.457t-.51.165z");
}

</style>
