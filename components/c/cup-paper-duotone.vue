<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p6o4tba2o.css';
import '../../css/f/fvoj6rvkh.css';
import '../../css/i/iy-tl4g0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p6o4tba2o"/><path class="fvoj6rvkh"/><path class="iy-tl4g0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cup-paper-duotone" /></template>
