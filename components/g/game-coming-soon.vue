<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="udrtzmb6n"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-coming-soon" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.udrtzmb6n {
  d: path("M13.957 13.5H9l-1.75 2.25q-.138.147-.296.272t-.332.225t-.361.175t-.383.121t-.397.063q-.2.017-.401.005t-.398-.054t-.386-.111t-.366-.165q-.176-.097-.337-.218t-.302-.264t-.261-.306t-.213-.34q-.095-.178-.162-.367q-.067-.19-.106-.387Q2.51 14.201 2.5 14L3 8.75q.012-.213.044-.424t.084-.418t.123-.409q.071-.201.161-.394q.09-.194.197-.378t.233-.358t.265-.333t.296-.308q.155-.146.324-.277q.168-.132.348-.246q.18-.115.37-.212t.389-.176t.403-.138q.205-.06.415-.1q.209-.04.422-.059q.213-.02.426-.02h9q.213 0 .426.02q.213.019.422.059q.21.04.415.1q.205.059.403.138t.389.176t.37.212t.348.246t.324.277q.155.147.296.308q.14.16.265.333t.233.358q.107.184.197.378q.09.193.161.394q.072.202.123.409t.084.418t.044.424l.402 4.218M5.75 9.5h3.5M7.5 7.75v3.5M15.25 10h.01m2.49-2h.01m-3.01 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
