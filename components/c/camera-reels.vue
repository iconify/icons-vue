<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ed0pqxdzw.css';
import '../../css/j/jolt8cvri.css';
import '../../css/i/ilyiwztto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ed0pqxdzw"/><path class="jolt8cvri"/><path class="ilyiwztto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:camera-reels" /></template>
