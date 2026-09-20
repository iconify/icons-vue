<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9m-1hblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-32-regular" /></template>
<style>
.j9m-1hblv {
  fill: currentColor;
  d: path("M17.076 2.041C24.306 2.591 30 8.631 30 16c0 7.732-6.268 14-14 14S2 23.732 2 16c0-3.97 1.654-7.556 4.308-10.103a1 1 0 0 1 1.384 1.444A11.96 11.96 0 0 0 4 16c0 6.627 5.373 12 12 12s12-5.373 12-12c0-6.316-4.881-11.494-11.076-11.965a1 1 0 0 1 .152-1.994m-8.365 8.358c-.59-1.075.612-2.277 1.687-1.687l.108.065c2.717 1.825 5.99 3.479 8.321 5.809a3 3 0 0 1-4.243 4.242c-.224-.224-.615-.751-1.037-1.339c-1.656-2.307-3.384-4.648-4.836-7.09");
}

</style>
