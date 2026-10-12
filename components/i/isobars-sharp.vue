<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="di849dqkd"/><path class="ve4fwxbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:isobars-sharp" /></template>
<style>
.di849dqkd {
  d: path("M9 3c1.88-.46 4.75-.29 6.5.25l2.496.77L19.5 6.25c.88 1.29 1 3.04 1.25 4.75s.58 3.92.25 5.5s-1.21 3.42-2.25 4s-2.67-.54-4-.5s-2.37.88-4 .75c-1.62-.12-4.46-.21-5.75-1.5S3.13 15.21 3 13c-.12-2.21.25-5.33 1.25-7S7.13 3.46 9 3Z");
}

.ve4fwxbcu {
  d: path("m10.5 6.5l2.688-.409L14.75 7.5l1.4 1.263L16 11.5c-.08 1.46-.67 3.88-1.75 4.75c-1.08.88-3.37.96-4.75.5l-2.607-.875L6 13.5l-.941-2.502L6.5 8.75c.75-1.17 2.63-2.04 4-2.25Zm-1 3v4m3-4v4m-3-2h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
