<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ijz_a9ldp"/><circle class="si3jgdbwb"/><circle class="fj7jfqy9k"/><path class="rhuzn2ivm"/><circle class="s-hn15u2q"/><circle class="ylefzo2zk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crowd" /></template>
<style>
.fj7jfqy9k {
  cx: 19px;
  cy: 11.5px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijz_a9ldp {
  cx: 5px;
  cy: 11.5px;
  r: 1.75px;
}

.rhuzn2ivm {
  d: path("M3.75 20.25h2.5A.75.75 0 0 0 7 19.5c0-1.9-.9-3.25-2-3.25S3 17.6 3 19.5a.75.75 0 0 0 .75.75m7 0h2.5a.75.75 0 0 0 .75-.75c0-1.9-.9-3.25-2-3.25s-2 1.35-2 3.25a.75.75 0 0 0 .75.75m7 0h2.5a.75.75 0 0 0 .75-.75c0-1.9-.9-3.25-2-3.25s-2 1.35-2 3.25a.75.75 0 0 0 .75.75");
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

.ylefzo2zk {
  cx: 15.5px;
  cy: 5px;
  r: 1.75px;
}

</style>
