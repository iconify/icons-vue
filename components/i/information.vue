<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="y94jm1b4c"><path class="mv9awbbbs"/><path class="geozw2bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:information" /></template>
<style>
.geozw2bre {
  d: path("M64 .41C28.93.41.41 28.93.41 64c0 35.06 28.52 63.59 63.58 63.59S127.58 99.07 127.58 64C127.59 28.93 99.06.41 64 .41m0 118C34 118.41 9.6 94 9.6 64S34 9.59 64 9.59S118.41 34 118.41 64.01C118.4 94 93.99 118.41 64 118.41");
}

.mv9awbbbs {
  d: path("M68.97 31.66c-.64-.49-1.38-.85-2.24-1.05c-.85-.19-1.75-.3-2.72-.3s-1.88.1-2.74.3c-.87.19-1.61.55-2.26 1.05c-.64.49-1.14 1.14-1.51 1.95c-.36.81-.55 1.83-.55 3.04c0 1.19.19 2.19.55 3.02c.37.81.87 1.48 1.51 1.97s1.39.85 2.26 1.06c.86.21 1.77.32 2.74.32c.96 0 1.87-.11 2.72-.32c.86-.21 1.6-.57 2.24-1.06s1.15-1.16 1.53-1.97c.38-.83.57-1.83.57-3.02c0-1.22-.19-2.24-.57-3.04q-.57-1.215-1.53-1.95M57.52 48.94h12.97v47.51H57.52z");
}

.y94jm1b4c {
  fill: var(--svg-color--40c0e7, #40c0e7);
}

</style>
