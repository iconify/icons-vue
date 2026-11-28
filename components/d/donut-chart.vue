<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdcn0mt7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdcn0mt7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:donut-chart" /></template>
