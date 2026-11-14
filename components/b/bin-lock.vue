<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x3dsz-lpk"/><path class="zvk3yiwvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-lock" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3dsz-lpk {
  d: path("m2.5 7l1-2.5h11l1 2.5Zm1 0l1.25 11.5h7.432m1.536-4.307L14.5 7");
}

.zvk3yiwvf {
  d: path("M5.25 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.978-1.138q-.204-.175-.457-.268q-.252-.094-.521-.094q-.074 0-.147.007t-.146.022t-.142.036q-.071.021-.139.049t-.133.063t-.126.076t-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126q-.035.065-.063.133t-.049.139q-.022.07-.036.142q-.015.073-.022.146T9.75 20t.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022t.147.007q.273 0 .529-.097q.256-.096.462-.277M15 17h6v4.5h-6Zm1.25 0v-1a1.75 1.75 0 0 1 3.5 0v1");
}

</style>
