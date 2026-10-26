<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsg68bc0n.css';
import '../../css/d/d3r56zbao.css';
import '../../css/z/zf8nsvb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="d3r56zbao"/><path class="zf8nsvb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:falling-leaves" /></template>
