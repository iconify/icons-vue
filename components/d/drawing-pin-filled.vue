<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb3u9ab5j.css';
import '../../css/c/cuyn6tgcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGgE5gcbVy" class="tb3u9ab5j"/></defs><g class="cuyn6tgcc"><use href="#SVGgE5gcbVy"/><use href="#SVGgE5gcbVy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:drawing-pin-filled" /></template>
