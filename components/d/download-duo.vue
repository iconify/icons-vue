<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/drfrgy0_d.css';
import '../../css/l/lw875-p4x.css';
import '../../css/y/yohw-bcjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="drfrgy0_d"/><path class="lw875-p4x"/><path class="wm-a yohw-bcjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:download-duo" /></template>
