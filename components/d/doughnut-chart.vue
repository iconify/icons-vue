<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfr5lhbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfr5lhbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:doughnut-chart" /></template>
