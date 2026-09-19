<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-c5dzbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-c5dzbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:choropleth-map" /></template>
