<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cls2e4bhq.css';
import '../../css/k/k8jdb4bay.css';
import '../../css/q/q8o3f8qgf.css';
import '../../css/i/i-fe1jb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="cls2e4bhq"/><path class="k8jdb4bay"/><path clip-rule="evenodd" class="q8o3f8qgf"/><path class="i-fe1jb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:file-print" /></template>
