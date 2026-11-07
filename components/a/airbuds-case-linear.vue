<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i-vl_3bog.css';
import '../../css/o/ozdm5k_ze.css';
import '../../css/u/u296q5x9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i-vl_3bog"/><path class="ozdm5k_ze"/><path class="u296q5x9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-case-linear" /></template>
