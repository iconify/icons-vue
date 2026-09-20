<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s8k31byhg"/><path class="bd3gqxb2t"/><path class="nuj5fcbnw"/><circle class="n51zhgbjx"/><path class="l5hr4v6mj"/><path class="fyry58ohr"/><path class="wz-7f95ge"/><path class="g6bt0tb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:bed" /></template>
<style>
.bd3gqxb2t {
  fill: var(--svg-color--196ca2, #196ca2);
  d: path("M6.14 60.18h118.03v8.44H6.14z");
}

.fyry58ohr {
  fill: var(--svg-color--875a3b, #875a3b);
  d: path("M125.25 89.79c0 2.97-1.84 5.37-4.11 5.37s-4.11-2.41-4.11-5.37V37.11c0-2.97 1.84-5.37 4.11-5.37s4.11 2.41 4.11 5.37z");
}

.g6bt0tb3z {
  fill: var(--svg-color--98aa30, #98aa30);
  d: path("M46.09 83.44h69.04c1.26 0 2.29-1.03 2.29-2.29V68.87H37.51v5.99c-.01 4.74 3.84 8.58 8.58 8.58");
}

.l5hr4v6mj {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M36.96 53.61c-.8-.45-.88-3.39-2.86-4.75c-1.42-.97-5.34-2.42-9.41-2.72c-3.76-.27-7.66.54-9.1 1.21c-2.18 1.02-2.73 3.91-3.59 4.22c-1.12.41-2 1.13-2.05 2.13c-.04.84.63 1.27 1.4 2.09c.57.59 1.42 3.16 2.77 4.01c1.33.83 5.17 1.44 9.31 1.78c4.17.34 8.63.41 10.09-.2c1.47-.62 2.73-3.01 3.39-3.51c.9-.68 1.63-.99 1.72-1.83c.12-1-.63-1.85-1.67-2.43");
}

.n51zhgbjx {
  cx: 8.22px;
  cy: 30.39px;
  r: 7.2px;
  fill: var(--svg-color--875a3b, #875a3b);
}

.nuj5fcbnw {
  fill: var(--svg-color--875a3b, #875a3b);
  d: path("M12.33 89.79c0 2.97-1.84 5.37-4.11 5.37s-4.11-2.41-4.11-5.37V37.11c0-2.97 1.84-5.37 4.11-5.37s4.11 2.41 4.11 5.37z");
}

.s8k31byhg {
  fill: var(--svg-color--875a3b, #875a3b);
  d: path("M6.14 68.62h118.03v12.31H6.14z");
}

.wz-7f95ge {
  fill: var(--svg-color--bdcf46, #bdcf46);
  d: path("M44.08 52.94s-6.41-.04-6.41 6.86c0 2.58-.03 9.91-.03 15.01c0 4.75 3.85 8.59 8.59 8.59h69.04c1.26 0 2.29-1.03 2.29-2.29V55.23c0-1.26-1.03-2.29-2.29-2.29z");
}

</style>
