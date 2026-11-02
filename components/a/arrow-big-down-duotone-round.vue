<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o5sbazbml"/><path class="h3-nkei3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-down-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h3-nkei3a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h-1a2 2 0 0 0-2 2v4a2 2 0 0 1-2 2H6c-.738 0-1.369.631-1 1l6 6a1.414 1.414 0 0 0 2 0l6-6c.369-.369-.262-1-1-1h-1a2 2 0 0 1-2-2V6a2 2 0 0 0-2-2z");
}

.o5sbazbml {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4h2a2 2 0 0 1 2 2v4a2 2 0 0 0 2 2h1c.738 0 1.369.631 1 1l-6 6a1.415 1.415 0 0 1-2 0l-6-6c-.369-.369.262-1 1-1h1a2 2 0 0 0 2-2V6a2 2 0 0 1 2-2");
}

</style>
