<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ot1c69gjd"/><path class="dp13b6b3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filter-brand" /></template>
<style>
.dp13b6b3a {
  d: path("m12.019 11.936l.341-1.991l-2.14-2.086l2.957-.429L14.5 4.75l1.323 2.68l2.957.429l-2.14 2.086l.344 2.006m-1.561.034L14.5 11.5l-.936.492M6.25 8.75h.01m7.74 6h7.25l-2.75 3.5v3l-1.75-1v-2Z");
}

.ot1c69gjd {
  d: path("M10.6 15H7.5l-5-6.25l5-6.25h14v9.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
