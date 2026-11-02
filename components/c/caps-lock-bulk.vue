<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="km1s1-b_i"/><path class="pk-3hg67t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caps-lock-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.km1s1-b_i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 18a2 2 0 0 1-2-2v-4H5a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l6-6a2.414 2.414 0 0 1 3.414 0l6 6c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14h-3v4a2 2 0 0 1-2 2Z");
}

.pk-3hg67t {
  d: path("M9 20h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
