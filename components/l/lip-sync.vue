<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tlu2tdbtd"/><path class="dnt3onvrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lip-sync" /></template>
<style>
.dnt3onvrq {
  d: path("M6.5 9.5q4.5-1.5 9 0q-4.5 3.5-9 0Zm8.75 10.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0V15.5m0 0l2.5 1.25");
}

.tlu2tdbtd {
  d: path("M15.983 13.712C14.382 15.023 12.691 15.5 11 15.5C8 15.5 5 14 2.5 9C5 5 7.5 4 9 4.5c1 .25 1.5.75 2 1.25c.5-.5 1-1 2-1.25C14.5 4 17 5 19.5 9c-.568 1.136-1.161 2.091-1.775 2.889");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
