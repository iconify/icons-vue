<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lw9fkn8oo.css';
import '../../css/f/fm3qqrbsa.css';
import '../../css/y/yxgzcxf7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lw9fkn8oo"/><path class="fm3qqrbsa"/><path class="ouiIcon__fillSecondary yxgzcxf7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-notebook" /></template>
