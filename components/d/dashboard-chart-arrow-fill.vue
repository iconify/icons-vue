<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfeabx60c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfeabx60c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-chart-arrow-fill" /></template>
