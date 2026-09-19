<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/je8i6b16f.css';
import '../../css/d/d3txjvobg.css';
import '../../css/u/uvgp29bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="je8i6b16f"/><path class="d3txjvobg"/><path class="uvgp29bxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:layers" /></template>
