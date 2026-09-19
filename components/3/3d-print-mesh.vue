<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdr-nrbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qdr-nrbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:3d-print-mesh" /></template>
