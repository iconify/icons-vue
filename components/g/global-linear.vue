<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvbhu7r3a.css';
import '../../css/m/m2m47owqp.css';
import '../../css/y/yirxaabex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvbhu7r3a"/><path class="m2m47owqp"/><path class="yirxaabex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:global-linear" /></template>
