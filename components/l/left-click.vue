<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6tm4o0sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:left-click" /></template>
<style>
.c6tm4o0sl {
  fill: currentColor;
  d: path("M11.7 18q-2.4-.125-4.05-1.85T6 12q0-2.5 1.75-4.25T12 6q2.425 0 4.15 1.65T18 11.7l-2.1-.625q-.325-1.35-1.4-2.212T12 8q-1.65 0-2.825 1.175T8 12q0 1.425.863 2.5t2.212 1.4zm8.825 4.5l-4.275-4.275L15 22l-3-10l10 3l-3.775 1.25l4.275 4.275z");
}

</style>
