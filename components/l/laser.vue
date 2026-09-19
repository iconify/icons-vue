<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eu06nbbze.css';
import '../../css/y/ynvzr33or.css';
import '../../css/o/o88qfn09d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="eu06nbbze"/><path class="ynvzr33or"/><path class="o88qfn09d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:laser" /></template>
