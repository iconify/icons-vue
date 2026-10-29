<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xv5hb_5sx.css';
import '../../css/g/g136touho.css';
import '../../css/b/bht756bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xv5hb_5sx"/><path class="g136touho wm-a"/><path class="bht756bnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:app-window-duo" /></template>
