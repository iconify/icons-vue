<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaw58obxy.css';
import '../../css/g/g90zm0rma.css';
import '../../css/u/uvvyx1dtx.css';
import '../../css/e/eys1nnoqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="uaw58obxy"><path class="g90zm0rma"/><path class="uvvyx1dtx"/><path class="eys1nnoqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:filter-one" /></template>
