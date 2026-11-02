<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xi5p6qb0l"/><path class="z7g9aab6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:github-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.xi5p6qb0l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 21v-3c0-.749.027-1.481.295-2.19c-2.083-.477-3.829-1.805-4.696-3.784C3.183 11.073 3 10.037 3 9c0-1.117.316-2.187.895-3.14c-.316-1.087-.242-2.183.177-3.231A1 1 0 0 1 5 2c.416 0 .833.067 1.241.141a16 16 0 0 1 2.832.814a13.1 13.1 0 0 1 5.854 0a16 16 0 0 1 2.832-.814C18.167 2.067 18.584 2 19 2c.409 0 .777.249.928.629c.419 1.048.493 2.144.177 3.231c.579.953.895 2.023.895 3.14c0 1.037-.183 2.073-.599 3.026c-.867 1.979-2.613 3.307-4.696 3.784c.268.709.295 1.441.295 2.19v3a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

.z7g9aab6q {
  d: path("M5.802 19.65a4.7 4.7 0 0 1-1.069-.856a11 11 0 0 1-.729-.876q-.454-.588-.658-.76C3.25 17.076 3.131 17 3 17a1 1 0 0 1 0-2c1.221 0 1.915.826 2.587 1.696c.344.446.702.931 1.202 1.215c.601.341 1.322.28 1.968.119a1 1 0 0 1 1.213.727a1 1 0 0 1-.727 1.213c-1.159.29-2.38.282-3.441-.32");
}

</style>
