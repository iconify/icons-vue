<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmz7stm5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmz7stm5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cubes-stacked-solid" /></template>
