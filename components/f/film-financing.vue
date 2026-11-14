<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjfqmp39r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:film-financing" /></template>
<style>
.yjfqmp39r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 18.5V6q0-.065.011-.129t.033-.125t.054-.117t.073-.106t.091-.092q.049-.043.105-.076t.116-.056t.124-.035l15.5-3q.072-.014.145-.014t.144.014q.072.015.139.042t.129.068q.061.041.112.092t.094.111q.041.06.069.128q.029.067.044.138l.75 3.5q.032.146.005.292q-.027.147-.108.272t-.204.21t-.269.116l-.021.005l-8.192 1.512H17.5q2.75 0 2.75 2.75v1.647Q19.655 13 19 13h-2q-2.071 0-3.536 1.464Q12 15.929 12 18q0 1.873 1.198 3.25H4.5q-2.75 0-2.75-2.75M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906M17 17q-1 0-1 1t1 1t1-1t-1-1");
}

</style>
