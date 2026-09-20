<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcxfff5pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcxfff5pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:analytics-board-graph-line-bold" /></template>
