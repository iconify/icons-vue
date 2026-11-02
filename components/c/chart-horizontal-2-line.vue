<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxtx3ffxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxtx3ffxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-horizontal-2-line" /></template>
