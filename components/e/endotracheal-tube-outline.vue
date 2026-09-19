<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wy1qmwb1c.css';
import '../../css/p/pfww3mgru.css';
import '../../css/d/d9kll0v9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wy1qmwb1c"/><path clip-rule="evenodd" class="pfww3mgru"/><path class="d9kll0v9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:endotracheal-tube-outline" /></template>
