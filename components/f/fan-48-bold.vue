<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl4xncchh.css';
import '../../css/q/qbfpednqz.css';
import '../../css/q/qewmfcczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rl4xncchh"/><path class="qbfpednqz"/><path class="qewmfcczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fan-48-bold" /></template>
