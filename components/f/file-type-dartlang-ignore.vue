<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jglvl5bxj"/><path class="z4az9xbkr"/><path class="pcvlploat"/><path class="mtou243sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dartlang-ignore" /></template>
<style>
.jglvl5bxj {
  fill: var(--svg-color--91d8a1, #91d8a1);
  d: path("M16.8 2.02a1.3 1.3 0 0 0-.92.37L7.34 7.36l8.51 8.58L26.1 26.18l2-3.51l-7.06-16.94l-3.28-3.28a1.3 1.3 0 0 0-.95-.43");
}

.mtou243sw {
  fill: var(--svg-color--91d8a1, #91d8a1);
  d: path("m7.37 7.4l8.7 8.72L26.1 26.15l-.73 3.82h-11.3l-3.97-4.03a6.5 6.5 0 0 1-1.6-3.61Z");
}

.pcvlploat {
  fill: var(--svg-color--368f49, #368f49);
  d: path("m7.3 7.35l8.76 8.73L26.1 26.12l3.82-.74V14.1l-3.98-3.98a6.4 6.4 0 0 0-3.6-1.6Z");
}

.z4az9xbkr {
  fill: var(--svg-color--368f49, #368f49);
  d: path("M7.36 7.34L2.4 15.87a1.3 1.3 0 0 0-.37.91a1.3 1.3 0 0 0 .38.93l4.12 4.1L22.5 28.1l3.62-2l-.1-.1l-10.05-10.06Z");
}

</style>
