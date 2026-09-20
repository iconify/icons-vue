<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yno5idtej.css';
import '../../css/u/uve6c28av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yno5idtej"/><path class="uve6c28av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-pie-filled" /></template>
