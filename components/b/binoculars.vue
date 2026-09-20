<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpd4dcb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gpd4dcb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:binoculars" /></template>
