<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zavkvob5y"/><path class="yrsbuph-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-subscriptions" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrsbuph-z {
  d: path("m3 6.5l7.5 4l7.5-4m-7.5 4v8m3.5-4h8V22h-8Zm0 3h8M16.5 13v2.5m3-2.5v2.5");
}

.zavkvob5y {
  d: path("m11.206 18.124l-.706.376l-7.5-4v-8l7.5-4l7.5 4v3.7");
}

</style>
