<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmtj78bqh.css';
import '../../css/g/gzrd91bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cmtj78bqh"/><path class="gzrd91bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-charging-48-bold" /></template>
