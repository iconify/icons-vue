<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="huek3zycs"/><path class="s4gy-lbcv"/><path class="homlwh54h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:frowning-face" /></template>
<style>
.homlwh54h {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M90.98 101.25c-1.4 0-2.69-.91-3.11-2.32c-2.85-9.49-12.9-16.37-23.89-16.37c-10.96 0-20.99 6.88-23.84 16.37a3.26 3.26 0 0 1-4.05 2.18a3.26 3.26 0 0 1-2.18-4.05c3.66-12.17 16.3-21 30.06-21c13.79 0 26.46 8.83 30.11 21c.52 1.72-.46 3.53-2.18 4.05c-.3.09-.61.14-.92.14M42 68c-4.49.04-8.17-4.27-8.22-9.62c-.05-5.37 3.55-9.75 8.04-9.79c4.48-.04 8.17 4.27 8.22 9.64c.05 5.36-3.55 9.73-8.04 9.77m44.11 0c4.48-.01 8.11-4.36 8.1-9.71c-.01-5.37-3.66-9.7-8.14-9.69c-4.49.01-8.13 4.36-8.12 9.73c.02 5.35 3.67 9.68 8.16 9.67");
}

.huek3zycs {
  fill: none;
  d: path("M.15 0H128v128H.15z");
}

.s4gy-lbcv {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M63.93 9.64C1.62 9.64.14 79.5.14 93.33s28.56 25.03 63.79 25.03c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.47-83.69-63.79-83.69");
}

</style>
