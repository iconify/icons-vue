<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bs00u1bfs.css';
import '../../css/k/ku9g8wbnx.css';
import '../../css/y/yr-jb4bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bs00u1bfs"/><path class="ku9g8wbnx"/><path clip-rule="evenodd" class="yr-jb4bim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-vertical-bold" /></template>
