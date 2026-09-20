<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oe9yg_bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autocorrect-32-regular" /></template>
<style>
.oe9yg_bkd {
  fill: currentColor;
  d: path("M14.74 7.686a1.5 1.5 0 0 1 2.52 0L20.697 13H19.5a6.5 6.5 0 1 0 5.308 2.746L24.342 15H29a1 1 0 1 0 0-2h-5.923L18.94 6.6c-1.379-2.133-4.499-2.133-5.878 0l-10.9 16.855A1 1 0 1 0 3.84 24.54zM15 19.5a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0");
}

</style>
