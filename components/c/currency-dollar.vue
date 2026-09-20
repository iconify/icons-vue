<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pn4sus4me.css';
import '../../css/q/q6dgyrq9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path vector-effect="non-scaling-stroke" class="pn4sus4me"/><path vector-effect="non-scaling-stroke" class="q6dgyrq9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:currency-dollar" /></template>
