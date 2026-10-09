<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oejyfcccr.css';
import '../../css/z/zv_mybbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oejyfcccr"/><path class="zv_mybbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-line-20-bold" /></template>
