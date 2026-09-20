<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dqgo5wbxe.css';
import '../../css/m/m390b8qby.css';
import '../../css/p/phi7aibzw.css';
import '../../css/a/aui1_r5dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dqgo5wbxe"/><path class="m390b8qby"/><path class="phi7aibzw"/><path class="aui1_r5dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-heart-linear" /></template>
