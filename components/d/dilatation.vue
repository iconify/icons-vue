<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_cu6h09n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g_cu6h09n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:dilatation" /></template>
