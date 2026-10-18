<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="dm0uzs1-f"><path class="xfetqbv9b"/><path class="u6vi0y4pc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-buf" /></template>
<style>
.dm0uzs1-f {
  stroke-width: var(--svg-stroke-width--0-092px, 0.092px);
}

.u6vi0y4pc {
  fill: var(--svg-color--161ede, #161ede);
  d: path("M10.015 8.02H8.02v21.946h1.995zm3.99 0H12.01v21.946h1.995zm3.99 0H16v21.946h1.995zm3.99 0H19.99v21.946h1.995zm3.991 0h-1.995v21.946h1.995zm3.99 0h-1.995v21.946h1.995z");
}

.xfetqbv9b {
  fill: var(--svg-color--77e1ff, #77e1ff);
  d: path("M4.03 2.034H2.033V23.98h1.995zm3.99 0H6.024V23.98H8.02zm3.99 0h-1.996V23.98h1.996zm3.99 0h-1.996V23.98H16zm3.99 0h-1.995V23.98h1.996zm3.99 0h-1.995V23.98h1.996z");
}

</style>
