<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-8grfeom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-8grfeom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chart-gantt" /></template>
