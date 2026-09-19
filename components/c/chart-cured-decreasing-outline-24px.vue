<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogcyy44xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogcyy44xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-cured-decreasing-outline-24px" /></template>
