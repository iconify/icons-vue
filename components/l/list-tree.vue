<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b42uobcxl.css';
import '../../css/o/oh-xkt67m.css';
import '../../css/h/h3xfvwbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b42uobcxl"/><path class="oh-xkt67m wm-a"/><path class="h3xfvwbbf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-tree" /></template>
