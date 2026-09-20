<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="v_suwkbbc"/><path class="q4nd5sa9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:brackets-round-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q4nd5sa9g {
  d: path("M40 128c0 58.29 34.67 80.25 36.15 81.16a8 8 0 0 1-8.27 13.7C66.09 221.78 24 195.75 24 128s42.09-93.78 43.88-94.86a8 8 0 0 1 8.26 13.7C74.54 47.83 40 69.82 40 128m148.12-94.86a8 8 0 0 0-8.27 13.7C181.33 47.75 216 69.71 216 128s-34.67 80.25-36.12 81.14a8 8 0 0 0 8.24 13.72C189.91 221.78 232 195.75 232 128s-42.09-93.78-43.88-94.86");
}

.v_suwkbbc {
  d: path("M224 128c0 64-40 88-40 88H72s-40-24-40-88s40-88 40-88h112s40 24 40 88");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
