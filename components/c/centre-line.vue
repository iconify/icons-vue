<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jeoaurmiu"/><path class="is4tjv2yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:centre-line" /></template>
<style>
.is4tjv2yr {
  d: path("M2.5 8.5h3v7h-3m19-7h-3v7h3M12 12h.01");
}

.jeoaurmiu {
  d: path("M2.5 4.5h19v15h-19Zm9.5 0v15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
