<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gq52txjpa"/><path class="pizvci63l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-explain" /></template>
<style>
.gq52txjpa {
  d: path("M14.49 17.612c-.853.329-1.689.787-2.49 1.388c-3-2.25-6.5-2.5-9.5-1.5v-13c3-1 6.5-.75 9.5 1.5c3-2.25 6.5-2.5 9.5-1.5v10.77M12 6v13");
}

.pizvci63l {
  d: path("M18.25 15q.5 2.75 3.25 3.25q-2.75.5-3.25 3.25q-.5-2.75-3.25-3.25q2.75-.5 3.25-3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
