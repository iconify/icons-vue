<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjoy21biv.css';
import '../../css/m/m97g7ra3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjoy21biv duoicon-secondary-layer"/><path class="duoicon-primary-layer m97g7ra3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:chart-pie" /></template>
