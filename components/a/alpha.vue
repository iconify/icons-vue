<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2ru7lcwo.css';
import '../../css/c/cuyn6tgcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGgxWCtbkt" class="g2ru7lcwo"/></defs><g class="cuyn6tgcc"><use href="#SVGgxWCtbkt"/><use href="#SVGgxWCtbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alpha" /></template>
