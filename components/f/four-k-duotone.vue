<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="darbm1s7t"/><path class="kmqn4eb8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:four-k-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.darbm1s7t {
  d: path("M224 48v160H32V48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kmqn4eb8z {
  d: path("M24 48a8 8 0 0 1 8-8h192a8 8 0 0 1 0 16H32a8 8 0 0 1-8-8m200 152H32a8 8 0 0 0 0 16h192a8 8 0 0 0 0-16M144 72a8 8 0 0 0-8 8v96a8 8 0 0 0 16 0v-29l13.09-15l28 48a8 8 0 1 0 13.82-8l-30.7-52.63L206 85.27a8 8 0 1 0-12-10.54l-42 48V80a8 8 0 0 0-8-8M88 176v-16H40a8 8 0 0 1-6.31-12.91l56-72A8 8 0 0 1 104 80v64h8a8 8 0 0 1 0 16h-8v16a8 8 0 0 1-16 0m0-32v-40.68L56.36 144Z");
}

</style>
