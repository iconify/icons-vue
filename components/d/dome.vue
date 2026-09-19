<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/h/h9-jrac4w.css';
import '../../css/e/efhy0xuho.css';
import '../../css/b/baquecuxi.css';
import '../../css/d/do5vkwb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="h9-jrac4w"/><path class="efhy0xuho"/><path class="baquecuxi"/><path class="do5vkwb4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dome" /></template>
