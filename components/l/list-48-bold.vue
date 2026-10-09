<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-p1p0bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h-p1p0bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-48-bold" /></template>
