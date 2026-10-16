<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj7euhm1y.css';
import '../../css/h/h17jzb6dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lj7euhm1y"/><path class="h17jzb6dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:data-pipeline-20-bold" /></template>
