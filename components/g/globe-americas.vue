<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-yiaqq3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:globe-americas" /></template>
<style>
.p-yiaqq3f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m2.851 2.112q4.152-2.595 7.313-.488q.088.059.157.14q.068.081.112.178q.043.097.058.202q.014.105-.001.21q-.223 1.566-2.327 3.187q-.449.346-.703.569q-.014.906 1.5 1.418q1.758.449 2.268 1.761q.487 1.252-.38 2.409l-.014.019l-2 2.5q-.046.057-.103.105t-.121.083q-.065.036-.135.058t-.144.03t-.147.002t-.145-.027t-.136-.054q-.066-.034-.124-.08q-.128-.103-.202-.251q-.276-.552-.681-1.605q-.625-1.626-1.157-2.178q-2.792-2.334-3.453-4.315q-.009-.027-.016-.055q-.653-2.612.448-3.712q.06-.061.133-.106");
}

</style>
