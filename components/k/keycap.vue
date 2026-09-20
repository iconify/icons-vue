<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qovi5mbkq"/><path class="g_lxh5b5u"/><path class="g_2zs9bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:keycap" /></template>
<style>
.g_2zs9bjv {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.g_lxh5b5u {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M121.7 6.3C120.2 4.9 118.2 4 116 4H12c-4.4 0-8 3.6-8 8v104c0 2.2.9 4.2 2.3 5.7l16.8-16.8h76c3.3 0 5.9-2.7 5.9-5.9V23z");
}

.qovi5mbkq {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.4 0-8 3.6-8 8v104c0 4.4 3.6 8 8 8h104c4.4 0 8-3.6 8-8V12c0-4.4-3.6-8-8-8");
}

</style>
