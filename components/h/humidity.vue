<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wzpei7bmr.css';
import '../../css/m/mmutxxbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="cuyn6tgcc"><path class="wzpei7bmr"/><path class="mmutxxbyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:humidity" /></template>
