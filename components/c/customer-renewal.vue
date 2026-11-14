<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qcw5wwb5t"/><path class="nyg8l_86n"/><path class="ya1gepf0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customer-renewal" /></template>
<style>
.nyg8l_86n {
  d: path("M12 12.25a3.25 3.25 0 1 1-3.25 3.25");
}

.qcw5wwb5t {
  d: path("M3.5 4.5h17V21h-17Zm4.5-2v4m8-4v4m-12.5 3h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ya1gepf0q {
  d: path("m7.5 17l1.25-1.5L10 17");
}

</style>
