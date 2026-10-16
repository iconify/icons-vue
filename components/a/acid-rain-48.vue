<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrqy-392k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yrqy-392k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:acid-rain-48" /></template>
