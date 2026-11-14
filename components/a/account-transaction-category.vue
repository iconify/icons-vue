<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="htjmzcb-r"/><path class="au6_zk5ea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-transaction-category" /></template>
<style>
.au6_zk5ea {
  d: path("M15 15h3.25l3 3L18 21.25l-3-3Z");
}

.htjmzcb-r {
  d: path("M14.078 21.247L12 20l-2.5 1.5L7.25 20L5 21.5v-19h14v9.7M8.5 6.5h7m-7 3.5h7m-7 3.5H12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
