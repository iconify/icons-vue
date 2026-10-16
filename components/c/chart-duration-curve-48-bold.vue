<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpel3hezc.css';
import '../../css/m/mu6uv0kwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="mu6uv0kwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-duration-curve-48-bold" /></template>
