<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pu2oi3b2e"/><path class="k75po9xas"/><circle class="ob8sdybbs"/><path class="d7psebc6y"/><path class="qct-9tbvb"/><path class="c6vzj5b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:fountain-pen" /></template>
<style>
.c6vzj5b4k {
  fill: var(--svg-color--bcaaa4, #bcaaa4);
  d: path("m70.7 65.39l-.67-.6c-.45-.4-.49-1.1-.09-1.55l25.19-28.15c.4-.45 1.1-.49 1.55-.09l.67.6c.45.4.49 1.1.09 1.55L72.25 65.31c-.4.45-1.1.48-1.55.08M57.53 86.17L45.16 74.9c-.89-.81-.96-2.2-.14-3.09c.81-.89 2.2-.96 3.09-.14l12.37 11.27c.89.81.96 2.2.14 3.09c-.81.89-2.2.95-3.09.14");
}

.d7psebc6y {
  fill: var(--svg-color--212121, #212121);
  d: path("m30.01 103.42l-10.18 15.44c-.26.37-.16.64-.81.6l-.41-.23l9.96-16.88z");
}

.k75po9xas {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M39.41 110.71c.28-7.19 5.75-19.78 8.18-25.03c.06-.12-.12-.21-.18-.09l-12.67 22.15c-.62 1.14-1.01 1.94-1.23 2.51l1.65-.4c.97-.25 2.61-.05 3.75.48z");
}

.ob8sdybbs {
  cx: 30.01px;
  cy: 101.82px;
  r: 2.2px;
  fill: var(--svg-color--212121, #212121);
}

.pu2oi3b2e {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M44.88 81.1L26.22 92.72l-8.25 24.93c-.45 1.37 1.2 2.45 2.27 1.48c5.72-5.16 15.91-13 19.98-7.58L50.7 85.43z");
}

.qct-9tbvb {
  fill: var(--svg-color--795548, #795548);
  d: path("M43.99 74.46c-1.89 1.33-2.09 4.06-.42 5.66l7.24 6.95a4.925 4.925 0 0 0 6.43.34s51.65-56.02 54.22-62.65c2.5-6.47-8.53-14.03-13.72-10.66c-5.11 3.32-53.75 60.36-53.75 60.36");
}

</style>
