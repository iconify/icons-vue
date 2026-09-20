<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="slibqdbmi"/><path class="jw_yhbbxl"/><path class="f0goeqbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-inc" /></template>
<style>
.f0goeqbfj {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M2 15v5h9v4l7-7l-7-6v4z");
}

.jw_yhbbxl {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M20.414 2H5v28h22V8.586ZM7 28V4h12v6h6v18Z");
}

.slibqdbmi {
  fill: var(--svg-color--gray, gray);
  d: path("M26 29H6V3h14l6 6z");
}

</style>
