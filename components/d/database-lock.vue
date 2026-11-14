<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b5vdcbblx"/><path class="bpldrgrwn"/><path class="f7w2tpo-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-lock" /></template>
<style>
.b5vdcbblx {
  d: path("M12.136 21.25H12c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.155");
}

.bpldrgrwn {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75c.743 0 1.463-.036 2.147-.102m5.675-2.076q.177-.278.178-.572");
}

.f7w2tpo-p {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m5.5 3.25h6v3.75h-6Zm1.5 0V16.5a1.5 1.5 0 0 1 3 0v1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
