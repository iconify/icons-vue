<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="slv365_-o"/><path class="rn2chmb4w"/><path class="n02h2n45h"/><path class="mox5uj9cg"/><path class="ov8-xub3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:database-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mox5uj9cg {
  d: path("M20 12C20 14.2091 16.4183 16 12 16C7.58172 16 4 14.2091 4 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n02h2n45h {
  d: path("M4 6C4 8.20914 7.58172 10 12 10C16.4183 10 20 8.20914 20 6C20 3.79086 16.4183 2 12 2C7.58172 2 4 3.79086 4 6Z");
}

.ov8-xub3w {
  d: path("M20 18C20 20.2091 16.4183 22 12 22C7.58172 22 4 20.2091 4 18");
}

.rn2chmb4w {
  d: path("M20 6V18");
}

.slv365_-o {
  d: path("M4 18V6");
}

</style>
