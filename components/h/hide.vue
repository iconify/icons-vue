<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e4koglhjf"/><path class="e3b88jbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hide" /></template>
<style>
.e3b88jbei {
  d: path("M9.934 14.38q-.223-.24-.398-.518q-.174-.278-.294-.583q-.12-.306-.181-.628Q9 12.328 9 12q0-.34.065-.673q.066-.334.194-.648q.128-.315.315-.599q.186-.284.423-.527M12.75 21.5v-14a1.25 1.25 0 0 1 2.5 0v4V5a1.25 1.25 0 0 1 2.5 0v6.5v-5a1.25 1.25 0 0 1 2.5 0v10c0 2-.75 2.75-1.5 3v2");
}

.e4koglhjf {
  d: path("M10.293 5.486C7.037 6.201 4.347 8.511 2.5 12c1.782 3.366 4.348 5.634 7.449 6.432");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
