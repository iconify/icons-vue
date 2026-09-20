<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdf-s7bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sdf-s7bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-geometric-polygon-polygon-octangle-design-geometric-shape-shapes" /></template>
