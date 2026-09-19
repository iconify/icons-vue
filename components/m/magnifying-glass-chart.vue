<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf6m7r4pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jf6m7r4pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:magnifying-glass-chart" /></template>
