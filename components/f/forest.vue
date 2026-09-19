<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-g8wbgam.css';
import '../../css/c/cuyn6tgcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGwVnWtYIz" class="e-g8wbgam"/></defs><g class="cuyn6tgcc"><use href="#SVGwVnWtYIz"/><use href="#SVGwVnWtYIz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:forest" /></template>
