<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8ohewbfz.css';
import '../../css/c/cuyn6tgcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<defs><path id="SVG67go7b2R" class="s8ohewbfz"/></defs><g class="cuyn6tgcc"><use href="#SVG67go7b2R"/><use href="#SVG67go7b2R"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:apple" /></template>
