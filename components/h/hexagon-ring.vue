<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg98qobio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hexagon-ring" /></template>
<style>
.fg98qobio {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 3h9.5q.099 0 .194.026q.096.025.181.075q.086.049.156.119t.119.156l4.75 8.25q.047.081.072.171t.028.183q.002.094-.018.185q-.021.091-.063.174l-.019.035l-4.75 8.25q-.049.086-.119.156t-.156.119q-.085.05-.181.075q-.095.026-.194.026h-9.5q-.096 0-.189-.024l-.006-.002q-.133-.036-.245-.117t-.188-.197l-.022-.036l-4.75-8.25q-.049-.085-.075-.18T1.75 12t.025-.194q.026-.095.075-.18l4.75-8.25q.049-.086.119-.156t.156-.119t.181-.075T7.25 3m9.066 16.5l4.319-7.5l-4.319-7.5H7.684L3.365 12l4.319 7.5z");
}

</style>
