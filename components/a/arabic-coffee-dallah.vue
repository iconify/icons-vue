<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ksa1ctbgy"/><path class="an8m1nbgp"/><path class="crmuqdbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arabic-coffee-dallah" /></template>
<style>
.an8m1nbgp {
  d: path("M8.5 11.75C6 11.25 4.5 9 4 6.5c-.15-.75.25-1.5 1-1.75M15 9.5c3.5 0 4.75 3.75 2 7.25");
}

.crmuqdbyd {
  d: path("M8 13.75h8L17.75 19a1.75 1.75 0 0 1-1.65 2.25H7.9A1.75 1.75 0 0 1 6.25 19ZM7.25 17h9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksa1ctbgy {
  d: path("M12 2.75v3M9.25 8.5a2.75 2.75 0 0 1 5.5 0Zm.75 0h4q.75 0 .92.73l.91 3.79q.17.73-.58.73h-6.5q-.75 0-.58-.73l.91-3.79q.17-.73.92-.73");
}

</style>
