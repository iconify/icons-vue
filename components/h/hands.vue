<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/zh4s4wylz.css';
import '../../css/r/r71t5ps3q.css';
import '../../css/m/m820zubuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="zh4s4wylz"/><path class="r71t5ps3q"/><path class="m820zubuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hands" /></template>
