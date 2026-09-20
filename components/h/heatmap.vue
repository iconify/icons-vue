<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7ibatb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i7ibatb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:heatmap" /></template>
