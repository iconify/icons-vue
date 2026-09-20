<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qovi5mbkq"/><path class="taetzn2em"/><path class="g_2zs9bjv"/><path class="arpazkb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:check-box-with-check" /></template>
<style>
.arpazkb1z {
  fill: var(--svg-color--fbf9f9, #fbf9f9);
  d: path("M38.8 105.5a8.86 8.86 0 0 1-8.7-6.2L15 53.8c-1.46-4.81 1.26-9.9 6.07-11.36c4.65-1.41 9.59 1.08 11.23 5.66l9.8 29.5L89.2 18c3.12-3.95 8.85-4.62 12.8-1.5s4.62 8.85 1.5 12.8L45.9 102a9.09 9.09 0 0 1-7.1 3.5");
}

.g_2zs9bjv {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qovi5mbkq {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.4 0-8 3.6-8 8v104c0 4.4 3.6 8 8 8h104c4.4 0 8-3.6 8-8V12c0-4.4-3.6-8-8-8");
}

.taetzn2em {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5C7.4 4 4 7.4 4 11.5v97.9c0 4.2 3.4 7.5 7.5 7.5h98.1c4.2 0 7.5-3.4 7.5-7.5V11.5c.2-4.1-3.3-7.5-7.4-7.5");
}

</style>
