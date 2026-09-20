<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cviv7ubzl.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wb0n91bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGye9ORcdG" class="cviv7ubzl"/></defs><g class="cuyn6tgcc"><use href="#SVGye9ORcdG"/><use href="#SVGye9ORcdG"/><path class="wb0n91bnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart-success-filled" /></template>
