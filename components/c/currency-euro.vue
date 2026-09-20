<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/q6dgyrq9a.css';
import '../../css/i/i7iqbpbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path vector-effect="non-scaling-stroke" class="q6dgyrq9a"/><path vector-effect="non-scaling-stroke" class="i7iqbpbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:currency-euro" /></template>
