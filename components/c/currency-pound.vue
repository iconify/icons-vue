<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/q6dgyrq9a.css';
import '../../css/l/l2gx7onal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path vector-effect="non-scaling-stroke" class="q6dgyrq9a"/><path vector-effect="non-scaling-stroke" class="l2gx7onal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:currency-pound" /></template>
