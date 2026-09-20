<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qlp2t04ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-panel-right-16-regular" /></template>
<style>
.qlp2t04ue {
  fill: currentColor;
  d: path("M14 5.5A2.5 2.5 0 0 0 11.5 3h-7A2.5 2.5 0 0 0 2 5.5v5A2.5 2.5 0 0 0 4.5 13h7a2.5 2.5 0 0 0 2.5-2.5zM9 4v8H4.5A1.5 1.5 0 0 1 3 10.5v-5A1.5 1.5 0 0 1 4.5 4zm1 0h1.5A1.5 1.5 0 0 1 13 5.5v5a1.5 1.5 0 0 1-1.5 1.5H10z");
}

</style>
