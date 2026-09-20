<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hkzeubbqo.css';
import '../../css/q/qkx_1d5id.css';
import '../../css/j/j5ec80dni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hkzeubbqo"/><path class="qkx_1d5id"/><path class="j5ec80dni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:finger-scan" /></template>
