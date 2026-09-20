<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="o579i9bep"/><path class="t1jddzhck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:ladder-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o579i9bep {
  d: path("M192 32v192H64V32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t1jddzhck {
  d: path("M192 24a8 8 0 0 0-8 8v32H72V32a8 8 0 0 0-16 0v192a8 8 0 0 0 16 0v-32h112v32a8 8 0 0 0 16 0V32a8 8 0 0 0-8-8m-8 56v40H72V80ZM72 176v-40h112v40Z");
}

</style>
