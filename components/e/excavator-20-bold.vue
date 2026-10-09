<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxnj49dbu.css';
import '../../css/p/pxuy9ccjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uxnj49dbu"/><path class="pxuy9ccjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:excavator-20-bold" /></template>
