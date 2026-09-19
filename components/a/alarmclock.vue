<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vgcmxccix.css';
import '../../css/x/xlramcbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":32};
const content = `<g class="cuyn6tgcc"><path class="vgcmxccix"/><path class="xlramcbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:alarmclock" /></template>
