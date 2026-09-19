<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jlkze7awy.css';
import '../../css/d/di0bxzb4v.css';
import '../../css/e/egneazb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="jlkze7awy"/><path class="di0bxzb4v"/><path class="egneazb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:file-arrow-up-right" /></template>
