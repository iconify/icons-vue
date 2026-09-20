<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jtoa-bt5u"/><path class="t1ik5b1ra"/><path class="gxy718l7l"/><path class="zr0ot55qq"/><path class="wuzarqbyn"/><path class="fgy2ecc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:classical-building" /></template>
<style>
.fgy2ecc5p {
  fill: var(--svg-color--bcd2d3, #bcd2d3);
  d: path("M5.3 108.99h117.2c1.05 0 1.9.85 1.9 1.9v10.67H3.39v-10.67c0-1.05.86-1.9 1.91-1.9");
}

.gxy718l7l {
  fill: var(--svg-color--eee, #eee);
  d: path("M11.24 34.49h104.68v2.92H11.24z");
}

.jtoa-bt5u {
  fill: var(--svg-color--64878e, #64878e);
  d: path("M14.38 54.6v41.75h98.9l-.27-41.75z");
}

.t1ik5b1ra {
  fill: var(--svg-color--8ab1b7, #8ab1b7);
  d: path("M13.47 37.41h100.54V47.6H13.47z");
}

.wuzarqbyn {
  fill: var(--svg-color--8ab1b7, #8ab1b7);
  d: path("M63.15 15.52L38.49 27.29c-.78.37-.51 1.54.35 1.54h49.08c.86 0 1.13-1.16.35-1.54L63.85 15.52c-.22-.1-.47-.1-.7 0M8.03 101.96h111.74c1.22 0 2.22.99 2.22 2.22v4.8H5.81v-4.8c0-1.22.99-2.22 2.22-2.22");
}

.zr0ot55qq {
  fill: var(--svg-color--bcd2d3, #bcd2d3);
  d: path("M11.88 47.59h103.63v7H11.88zm-.08 48.76h103.98c1.25 0 2.26 1.01 2.26 2.26v3.8H9.54v-3.8c0-1.24 1.01-2.26 2.26-2.26m96.71-38.73V54.6H96.95v3.02h2.07l-1.18 38.73h10.67l-1.63-38.73zm-53.77 0h1.86V54.6H45.03v3.02h1.85l-1.41 38.73h10.68zm-25.96 0h1.86V54.6H19.07v3.02h1.86l-1.41 38.73h10.67zm53.78-3.02H70.98v1.09h.01v1.93h1.85l-1.41 38.73h10.68L80.7 57.62h1.85v-1.93h.01zM8.06 32.93L62.72 6.91c.54-.26 1.18-.26 1.72 0l54.66 26.02v4.63H8.06z");
}

</style>
