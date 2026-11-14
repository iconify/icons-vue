<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="znjioycfi"/><path class="enuzerbiy"/><path class="t5blqhb3d"/><path class="ah55kfbgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loyalty-cashback" /></template>
<style>
.ah55kfbgu {
  d: path("M19.25 16.75C19 16.25 18.6 16 18 16c-.7 0-1.25.4-1.25 1c0 1.25 2.5.75 2.5 2c0 .6-.55 1-1.25 1c-.6 0-1-.25-1.25-.75");
}

.enuzerbiy {
  fill: currentColor;
  d: path("m8.75 6.25l1.176 2.882l3.104.227l-2.378 2.009l.743 3.023L8.75 12.75l-2.645 1.641l.743-3.023L4.47 9.359l3.104-.227Z");
}

.t5blqhb3d {
  d: path("M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znjioycfi {
  d: path("M11.7 20H2.5V4h19v8.5");
}

</style>
