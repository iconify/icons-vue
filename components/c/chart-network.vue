<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa-vynbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pa-vynbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-network" /></template>
