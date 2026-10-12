<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rl9nqebkg"/><path class="r9xqs9yoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brain-dump-sharp" /></template>
<style>
.r9xqs9yoe {
  d: path("M6 12.5h2.75V10M18 12.5h-2.75V10m-6.5 5.25l-1.5.5v1.5m8-2l1.5.5v1.5");
}

.rl9nqebkg {
  d: path("M12 4.75a3.5 3.5 0 0 0-6.5 1.5a3.5 3.5 0 0 0-1.75 5a4 4 0 0 0 .75 5.5a4 4 0 0 0 4 4a3 3 0 0 0 3.5-1a3 3 0 0 0 3.5 1a4 4 0 0 0 4-4a4 4 0 0 0 .75-5.5a3.5 3.5 0 0 0-1.75-5a3.5 3.5 0 0 0-6.5-1.5Zm0 0v15");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
