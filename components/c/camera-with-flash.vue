<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nf5ggjbhz.css';
import '../../css/r/rngcxkb7w.css';
import '../../css/o/oirt199-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="nf5ggjbhz"/><path class="rngcxkb7w"/><path class="oirt199-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:camera-with-flash" /></template>
