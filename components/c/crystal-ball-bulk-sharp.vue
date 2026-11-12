<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b85damirh"/><path class="wmp6jj3dr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-bulk-sharp" /></template>
<style>
.b85damirh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.275 16.039c.424.121.725.52.725.961v4c0 .55-.45 1-1 1H5c-.55 0-1-.45-1-1v-4c0-.441.301-.84.725-.961a8.7 8.7 0 0 1-1.619-5.591a9.2 9.2 0 0 1 1.731-4.845A8.7 8.7 0 0 1 9.104 2.46a9.28 9.28 0 0 1 5.792 0c.868.29 1.687.718 2.42 1.266a9 9 0 0 1 3.059 4.176c.978 2.741.61 5.767-1.1 8.137");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wmp6jj3dr {
  d: path("M8.315 8.443c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 12 6a1 1 0 0 1 0 2c-.533 0-1.039.207-1.414.586A1.98 1.98 0 0 0 10 10a1 1 0 0 1-2 0a4 4 0 0 1 .315-1.557M19 18H5a1 1 0 0 1 0-2h14a1 1 0 0 1 0 2");
}

</style>
