<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lm511ce7e.css';
import '../../css/t/tzovut_xs.css';
import '../../css/j/j0x6rylzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lm511ce7e"/><path class="tzovut_xs"/><path class="j0x6rylzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:chat" /></template>
