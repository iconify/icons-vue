<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydne_bc6v.css';
import '../../css/b/bf53s552u.css';
import '../../css/c/chv70ybrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ydne_bc6v"><path class="bf53s552u"/><path class="chv70ybrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ai-science-robot" /></template>
