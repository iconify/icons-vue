<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ijz_a9ldp"/><circle class="si3jgdbwb"/><circle class="fj7jfqy9k"/><path class="ko_mxmksq"/><circle class="s-hn15u2q"/><circle class="ylefzo2zk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crowd-sharp" /></template>
<style>
.fj7jfqy9k {
  cx: 19px;
  cy: 11.5px;
  r: 1.75px;
}

.ijz_a9ldp {
  cx: 5px;
  cy: 11.5px;
  r: 1.75px;
}

.ko_mxmksq {
  d: path("M3.75 20.25H7v-.75c0-1.9-.9-3.25-2-3.25S3 17.6 3 19.5v.75zm7 0H14v-.75c0-1.9-.9-3.25-2-3.25s-2 1.35-2 3.25v.75zm7 0H21v-.75c0-1.9-.9-3.25-2-3.25s-2 1.35-2 3.25v.75z");
}

.s-hn15u2q {
  cx: 8.5px;
  cy: 5px;
  r: 1.75px;
}

.si3jgdbwb {
  cx: 12px;
  cy: 11.5px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ylefzo2zk {
  cx: 15.5px;
  cy: 5px;
  r: 1.75px;
}

</style>
