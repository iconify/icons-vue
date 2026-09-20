<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hf786h7dg"/><path class="kmwa31bjk"/><path class="pqngn6bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:face-with-stuck-out-tongue" /></template>
<style>
.hf786h7dg {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M127.22 93.42c0 13.86-28.29 25.1-63.22 25.1c-34.92 0-63.23-11.24-63.23-25.1C.77 79.55 2.24 9.48 64 9.48c61.77 0 63.22 70.06 63.22 83.94");
}

.kmwa31bjk {
  fill: var(--svg-color--d7598b, #d7598b);
  d: path("M47.44 85.6c3.85 4.48.76 17.64 10.25 22.37c1.77.89 4.13 1.35 6.55 1.34v-.08v.08c2.42-.04 4.77-.55 6.52-1.47c9.4-4.92 6.04-18.02 9.8-22.58z");
}

.pqngn6bec {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64 89.76c-11.65 0-23.3-3.14-33.25-9.41a3.007 3.007 0 0 1-.94-4.14c.88-1.4 2.74-1.82 4.14-.94c17.97 11.34 42.12 11.34 60.09 0c1.4-.88 3.25-.46 4.14.94s.46 3.25-.94 4.14C87.3 86.63 75.65 89.76 64 89.76M42.21 65.19c-4.49.04-8.17-4.27-8.22-9.62c-.05-5.37 3.55-9.75 8.04-9.79c4.48-.04 8.17 4.27 8.22 9.64c.05 5.36-3.55 9.73-8.04 9.77m44.11 0c4.48-.01 8.11-4.36 8.1-9.71c-.01-5.37-3.66-9.7-8.14-9.69c-4.49.01-8.13 4.36-8.12 9.73c.02 5.35 3.67 9.68 8.16 9.67");
}

</style>
