<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5bd6_65p"/><path class="lsk3v1baa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:accessibility-test" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lsk3v1baa {
  d: path("M11 9.5V13h3.5l.962 2.308M8.5 12.75q-.104.104-.198.219q-.094.114-.176.236q-.082.123-.151.253q-.07.131-.126.267q-.057.136-.1.278q-.043.141-.071.286q-.029.145-.044.291q-.014.147-.014.295t.014.295t.044.291q.028.145.071.286q.043.142.1.278q.056.136.126.267q.069.13.151.253q.082.122.176.236q.094.115.198.219q.083.083.172.159t.183.145q.095.069.194.13q.1.061.204.115q.104.053.212.098t.219.082t.225.065t.229.046t.232.029t.234.011q.117.001.233-.007q.117-.009.233-.026q.115-.017.229-.043q.115-.027.226-.062q.112-.035.22-.078q.109-.044.214-.096M14.75 18l2 2L21 15.75");
}

.o5bd6_65p {
  d: path("M12.75 21.5a9.5 9.5 0 1 1 8.75-8.75M11 7h.01");
}

</style>
