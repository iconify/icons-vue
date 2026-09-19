<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsubc8bso.css';
import '../../css/r/rmib92a5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vsubc8bso"/><path class="rmib92a5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:alarm-add" /></template>
