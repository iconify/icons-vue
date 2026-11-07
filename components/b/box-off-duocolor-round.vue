<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o64q_mbin"/><path class="siae8piri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o64q_mbin {
  stroke-opacity: 0.4;
  d: path("M3.32 6.602L7.83 8.83M12 13v8.77m2.374-12.053l6.306-3.115M2 3l19 19");
}

.siae8piri {
  d: path("m4.636 5.636l-.522.258A2 2 0 0 0 3 7.687v8.626a2 2 0 0 0 1.114 1.793l7 3.457a2 2 0 0 0 1.772 0l5.139-2.538M8.423 3.766l2.691-1.329a2 2 0 0 1 1.772 0l7 3.457A2 2 0 0 1 21 7.687v8.656");
}

</style>
