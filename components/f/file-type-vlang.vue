<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3ku07bgi"/><path class="rjjh6hw7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-vlang" /></template>
<style>
.f3ku07bgi {
  fill: var(--svg-color--536b8a, #536b8a);
  d: path("m20.467 29.288l9.485-26.375a.5.5 0 0 0-.566-.728l-7.459.715a1.46 1.46 0 0 0-1.141.9l-8.779 25.206a.573.573 0 0 0 .578.813h7.26a.66.66 0 0 0 .577-.4Z");
}

.rjjh6hw7j {
  fill: var(--svg-color--5d87bf, #5d87bf);
  d: path("m2.614 2.185l7.459.719a1.47 1.47 0 0 1 1.142.9l8.965 25.609a.286.286 0 0 1-.289.406h-7.306a1.31 1.31 0 0 1-1.152-.81L2.048 2.913a.5.5 0 0 1 .566-.728");
}

</style>
