<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rzdywtb4l.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/e/e7nou4btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rzdywtb4l"/><path class="qr4ochb5c wm-s"/><path class="e7nou4btv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lightbulb-off-duo" /></template>
