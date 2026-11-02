<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3jb7-bgm"/><path class="doaj1tf4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-top-duocolor-sharp" /></template>
<style>
.doaj1tf4c {
  d: path("M4 8v12h6V8Zm10 0v8h6V8Z");
}

.n3jb7-bgm {
  stroke-opacity: 0.4;
  d: path("M3 4h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
