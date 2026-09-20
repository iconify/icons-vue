<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsam32rsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hsam32rsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:analytics-graph-bar-horizontal" /></template>
