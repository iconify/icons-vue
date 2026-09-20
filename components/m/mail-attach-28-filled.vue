<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<g class="cuyn6tgcc"><path class="lfk20tzqu"/><path class="bhcokzbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-attach-28-filled" /></template>
<style>
.bhcokzbps {
  d: path("M21.954 4.1a2.077 2.077 0 0 1 2.938 2.938L18.64 13.3a.672.672 0 0 1-.95-.95l5.084-5.072a.75.75 0 1 0-1.06-1.062L16.63 11.29a2.172 2.172 0 0 0 3.07 3.071l6.253-6.263a3.577 3.577 0 0 0-5.06-5.058l-5.677 5.677a.75.75 0 1 0 1.06 1.06z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lfk20tzqu {
  d: path("m20.408 15.067l4.585-4.593v9.27a3.25 3.25 0 0 1-3.064 3.243l-.185.005H6.25a3.25 3.25 0 0 1-3.244-3.064L3 19.743v-9.622l10.65 5.54a.75.75 0 0 0 .692 0l1.436-.747q.069.08.144.154a3.17 3.17 0 0 0 4.485 0M6.248 5H17.52l-3.011 3.01a1.75 1.75 0 0 0 1.07 2.979a3.17 3.17 0 0 0-.494 2.595l-1.088.566L3 8.432v-.184a3.25 3.25 0 0 1 3.065-3.244zm15.706-.9l-5.678 5.677Z");
}

</style>
