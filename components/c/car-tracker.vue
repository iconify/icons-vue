<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_1l4cbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-tracker" /></template>
<style>
.j_1l4cbbz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.81 11.75H3.5q-1.75 0-1.75-1.75V7.5q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l2.815-1.174l2.379-3.091q.052-.069.119-.123q.066-.055.144-.093t.161-.057t.17-.02h7q.165 0 .316.07q.15.069.257.196l2.602 3.075l1.52.435Q21.25 6.421 21.25 8v2q0 1.75-1.75 1.75h-2.31q-.345 2-2.69 2t-2.69-2H9.19q-.345 2-2.69 2t-2.69-2m15.69-1.5h-2.31q-.345-2-2.69-2t-2.69 2H9.19q-.345-2-2.69-2t-2.69 2H3.5q-.25 0-.25-.25V8l2.538-1.058q.185-.076.306-.235L8.369 3.75h6.283l2.525 2.984q.148.175.367.237l1.75.5l.024.007q.432.108.432.522v2q0 .25-.25.25m-1.28 12.28q-2.97-2.969-2.97-3.78q0-3.5 3.5-3.5t3.5 3.5q0 .811-2.97 3.78q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094m2.53-3.78q0 .168-2 2.187q-2-2.019-2-2.187q0-2 2-2t2 2");
}

</style>
