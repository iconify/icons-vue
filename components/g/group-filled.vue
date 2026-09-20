<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fal574quc.css';
import '../../css/t/tb5ln68hg.css';
import '../../css/p/p33g7ob5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fal574quc"/><path class="tb5ln68hg"/><path class="p33g7ob5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:group-filled" /></template>
