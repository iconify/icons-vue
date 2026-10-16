<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-ttanbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m-ttanbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-funnel-20-bold" /></template>
