<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hu30fdbrj.css';
import '../../css/w/wz6jt76ak.css';
import '../../css/q/q4xke4y0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hu30fdbrj"/><path class="wz6jt76ak"/><path class="q4xke4y0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-check-linear" /></template>
