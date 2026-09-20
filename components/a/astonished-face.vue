<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q34ia8-ee"/><path class="vxpua1b4v"/><path class="cyuv8x6pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:astonished-face" /></template>
<style>
.cyuv8x6pl {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M83.84 67.05c-14.4-.76-20.24 7.92-31.81 7.92c-6.42 0-10.41-2.39-17.84-.55c-5.71 1.41-7.86 7.02-7.86 10.1s2.16 8.69 7.86 10.1c7.43 1.83 11.42-.55 17.84-.55c11.57 0 17.4 8.67 31.81 7.92c10.25-.54 17.87-7.74 17.83-17.47c.04-9.74-7.58-16.94-17.83-17.47");
}

.q34ia8-ee {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64 9.56C1.59 9.56.12 79.52.12 93.36c0 13.86 28.59 25.08 63.88 25.08c35.28 0 63.88-11.22 63.88-25.08c0-13.84-1.48-83.8-63.88-83.8");
}

.vxpua1b4v {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M42.25 63.03c-6.21.06-11.31-5.91-11.38-13.32c-.07-7.44 4.92-13.5 11.13-13.56c6.21-.05 11.31 5.91 11.38 13.35c.06 7.42-4.92 13.47-11.13 13.53m44.07-3.84c4.43-.01 8.02-4.31 8.01-9.6c-.01-5.31-3.62-9.6-8.05-9.58c-4.44.01-8.04 4.31-8.03 9.62c.02 5.29 3.63 9.57 8.07 9.56");
}

</style>
