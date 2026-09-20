<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="icokhacaz"><path class="xjvfc9bxx"/><path class="y1_0gacbv"/><path class="lsh1ysbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dropzone" /></template>
<style>
.icokhacaz {
  fill: var(--svg-color--028bf4, #028bf4);
}

.lsh1ysbqv {
  d: path("M128 0H0v256h128c70.692 0 128-57.308 128-128S198.692 0 128 0m0 234.667H21.333V128C21.333 69.092 69.092 21.333 128 21.333S234.667 69.092 234.667 128S186.912 234.667 128 234.667");
}

.xjvfc9bxx {
  d: path("M128 42.667c-47.129 0-85.333 38.204-85.333 85.333v85.333H128c47.129 0 85.333-38.204 85.333-85.333S175.13 42.667 128 42.667M128 192H64v-64c0-35.346 28.654-64 64-64s64 28.654 64 64s-28.65 64-64 64");
}

.y1_0gacbv {
  d: path("M128 85.333c-23.563 0-42.667 19.104-42.667 42.667v42.667H128c23.563 0 42.667-19.104 42.667-42.667S151.563 85.333 128 85.333m0 64h-21.333V128c0-11.78 9.553-21.333 21.333-21.333s21.333 9.553 21.333 21.333s-9.55 21.333-21.333 21.333");
}

</style>
