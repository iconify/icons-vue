<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b1jrer2eh"/><path class="ta5pgbb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-duotone-sharp" /></template>
<style>
.b1jrer2eh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.275 16.039c.424.121.725.52.725.961v4c0 .55-.45 1-1 1H5c-.55 0-1-.45-1-1v-4c0-.441.301-.84.725-.961a8.7 8.7 0 0 1-1.619-5.591a9.2 9.2 0 0 1 1.731-4.845A8.7 8.7 0 0 1 9.104 2.46a9.28 9.28 0 0 1 5.792 0c.868.29 1.687.718 2.42 1.266a9 9 0 0 1 3.059 4.176c.978 2.741.61 5.767-1.1 8.137");
}

.ft5dv1b6b {
  fill: none;
}

.ta5pgbb0c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17C1.262 12.302 4.584 3 12 3s10.738 9.302 5 14M5 17h14v4H5Zm4-7a3 3 0 0 1 3-3");
}

</style>
