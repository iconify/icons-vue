<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ik19wxu2o.css';
import '../../css/q/q9hb2zs7n.css';
import '../../css/r/ryuyffwfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ik19wxu2o"/><path class="q9hb2zs7n wm-shadow"/><path class="ryuyffwfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-justify-engrave" /></template>
