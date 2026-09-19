<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j0lod_6vu.css';
import '../../css/p/pjnhxqb5g.css';
import '../../css/l/lvoxeyxvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="j0lod_6vu"/><path class="pjnhxqb5g"/><path class="lvoxeyxvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hdd-stack" /></template>
