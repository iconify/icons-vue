<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-cjo9ueo.css';
import '../../css/p/p5oqracae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-cjo9ueo"/><path class="p5oqracae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-line-chart" /></template>
