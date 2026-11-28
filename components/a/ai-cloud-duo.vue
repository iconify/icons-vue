<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr9fe-bgg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x8si0cb1k.css';
import '../../css/x/x8k2v8omx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr9fe-bgg secondary"/><g class="dt0cm9dhy primary"><path class="x8si0cb1k"/><path class="x8k2v8omx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-cloud-duo" /></template>
