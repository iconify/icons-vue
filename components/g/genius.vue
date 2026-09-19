<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nk4syz2ss.css';
import '../../css/u/u9wri7bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":32};
const content = `<g class="cuyn6tgcc"><path class="nk4syz2ss"/><path class="u9wri7bhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:genius" /></template>
