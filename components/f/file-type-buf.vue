<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="dm0uzs1-f"><path class="sseulijiw"/><path class="h-a9u-plz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-buf" /></template>
<style>
.dm0uzs1-f {
  stroke-width: var(--svg-stroke-width--0-092px, 0.092px);
}

.h-a9u-plz {
  fill: var(--svg-color--161ede, #161ede);
  d: path("M10.015 8.02H8.02v21.947h1.995zm3.991 0H12.01v21.947h1.996zm3.989 0H16v21.947h1.995zm3.99 0H19.99v21.947h1.995zm3.991 0h-1.995v21.947h1.995zm3.99 0h-1.995v21.947h1.995z");
}

.sseulijiw {
  fill: var(--svg-color--77e1ff, #77e1ff);
  d: path("M4.03 2.034H2.033v21.947h1.995zm3.99 0H6.024v21.947H8.02zm3.99 0h-1.995v21.947h1.995zm3.99 0h-1.995v21.947H16zm3.99 0h-1.995v21.947h1.996zm3.99 0h-1.995v21.947h1.996z");
}

</style>
