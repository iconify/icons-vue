<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p4rxo9gpl.css';
import '../../css/o/or9a92b3r.css';
import '../../css/t/t076rfbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="p4rxo9gpl"/><path class="or9a92b3r"/><path class="t076rfbic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:compass-dot" /></template>
