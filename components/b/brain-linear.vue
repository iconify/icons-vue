<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pn6x5_bim.css';
import '../../css/a/awmsyvf0e.css';
import '../../css/c/cyyxj_bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pn6x5_bim"/><path class="awmsyvf0e"/><path class="cyyxj_bur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:brain-linear" /></template>
