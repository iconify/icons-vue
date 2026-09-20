<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o205f_btu"/><path class="vlfltdbow"/><path class="hqezggvkx"/><path class="g_2zs9bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:eject-button" /></template>
<style>
.g_2zs9bjv {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hqezggvkx {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M61.426 80h29.2a2.68 2.68 0 0 0 2.3-4l-29.2-50.7a2.63 2.63 0 0 0-3.58-1.02c-.43.24-.79.59-1.02 1.02L29.926 76a2.674 2.674 0 0 0 1.01 3.65c.39.22.84.34 1.29.35zm-31.8 18.2v-8.3c-.01-.99.79-1.79 1.78-1.8h60.32c.99-.01 1.79.79 1.8 1.78v8.32c.01.99-.79 1.79-1.78 1.8h-60.32c-.99.01-1.79-.79-1.8-1.78z");
}

.o205f_btu {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.vlfltdbow {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
