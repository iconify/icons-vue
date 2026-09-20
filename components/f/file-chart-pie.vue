<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/ah1iiubfc.css';
import '../../css/i/i6tcmibtw.css';
import '../../css/r/rzb8izb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ah1iiubfc"/><path class="i6tcmibtw"/><path class="rzb8izb8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:file-chart-pie" /></template>
