<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/em_q5npjq.css';
import '../../css/m/ml0cb1b5h.css';
import '../../css/s/sdokwhbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="em_q5npjq"/><path class="ml0cb1b5h"/><path class="sdokwhbfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-broken" /></template>
