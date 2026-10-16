<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhp5-v54c.css';
import '../../css/k/ku-g4jbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zhp5-v54c"/><path class="ku-g4jbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-network-48-bold" /></template>
