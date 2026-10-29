<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vrui9ubxc.css';
import '../../css/u/uanjz8m2o.css';
import '../../css/w/wri5opbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vrui9ubxc"/><path class="uanjz8m2o wm-a"/><path class="wri5opbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-tree-duo" /></template>
