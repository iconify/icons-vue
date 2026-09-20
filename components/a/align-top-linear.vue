<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m7r8ebbdl.css';
import '../../css/c/cur27zb3c.css';
import '../../css/c/cts3slb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m7r8ebbdl"/><path class="cur27zb3c"/><path class="cts3slb-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-top-linear" /></template>
