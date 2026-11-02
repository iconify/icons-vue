<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q308zk7sk"/><path class="topps6brl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:github-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q308zk7sk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 18c0-.749.027-1.481.295-2.19c-2.083-.477-3.829-1.805-4.696-3.784C3.183 11.073 3 10.037 3 9c0-1.117.316-2.187.895-3.14c-.316-1.087-.242-2.183.177-3.231A1 1 0 0 1 5 2c.416 0 .833.067 1.241.141a16 16 0 0 1 2.832.814a13.1 13.1 0 0 1 5.854 0a16 16 0 0 1 2.832-.814C18.167 2.067 18.584 2 19 2c.409 0 .777.249.928.629c.419 1.048.493 2.144.177 3.231c.579.953.895 2.023.895 3.14c0 1.037-.183 2.073-.599 3.026c-.867 1.979-2.613 3.307-4.696 3.784c.268.709.295 1.441.295 2.19v3a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Z");
}

.topps6brl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21v-3c0-1 0-2 1-3c-3 0-6-2-6-6c0-1.3.5-2.3 1-3q-.6-1.5 0-3s1.5 0 4 1q3-.75 6 0c2.5-1 4-1 4-1q.6 1.5 0 3c.5.7 1 1.7 1 3c0 4-3 6-6 6c1 1 1 2 1 3v3m-6-2c-4 1-4-3-6-3");
}

</style>
