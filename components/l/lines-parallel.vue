<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2b_j-ktc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lines-parallel" /></template>
<style>
.i2b_j-ktc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.291 3.756l-5.5 16q-.024.07-.034.143t-.006.147t.024.145t.051.138q.032.066.077.125t.1.108t.12.086q.063.037.133.061q.141.049.29.04t.283-.075t.233-.177t.147-.253l5.5-16q.024-.07.034-.143t.006-.147t-.024-.145q-.019-.072-.051-.138t-.077-.125t-.1-.108t-.12-.086q-.063-.037-.133-.061q-.141-.049-.29-.04t-.283.075t-.233.177q-.099.112-.147.253m0 16l5.5-16q.024-.07.061-.133q.037-.064.086-.12t.108-.1q.058-.045.125-.077q.066-.032.138-.051q.071-.019.145-.024q.074-.004.147.006t.143.034q.141.048.253.147q.111.099.177.233t.075.283t-.04.29l-5.5 16q-.048.141-.147.253q-.099.111-.233.177t-.283.075t-.29-.04q-.07-.024-.133-.061q-.064-.037-.12-.086t-.1-.108t-.077-.125t-.051-.138q-.019-.071-.024-.145q-.004-.074.006-.147t.034-.143");
}

</style>
