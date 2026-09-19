<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj9yn6a4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="aj9yn6a4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:bus-map" /></template>
