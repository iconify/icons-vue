<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdxs57r6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vdxs57r6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:growth-chart-stroke-12" /></template>
