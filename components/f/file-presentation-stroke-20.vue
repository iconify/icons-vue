<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka08yacpr.css';
import '../../css/y/ypv4l3ivv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ka08yacpr"/><path class="ypv4l3ivv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-presentation-stroke-20" /></template>
