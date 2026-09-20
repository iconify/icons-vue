<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y-ioddvys.css';
import '../../css/y/y44uunbxa.css';
import '../../css/u/uvx097b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y-ioddvys"/><path class="y44uunbxa"/><path class="uvx097b-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:earth-linear" /></template>
