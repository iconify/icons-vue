<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/m/m_vk58bve.css';
import '../../css/m/m_9bs70wo.css';
import '../../css/z/zjedaobvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="m_vk58bve"/><path class="m_9bs70wo"/><path class="zjedaobvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:camera-four" /></template>
