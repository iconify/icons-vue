<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p61yw8uba.css';
import '../../css/g/g_x203bjf.css';
import '../../css/e/egfkty-mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p61yw8uba"/><path class="g_x203bjf"/><path class="egfkty-mb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-koala" /></template>
