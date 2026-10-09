<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqla65ydx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aqla65ydx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-rain-20-bold" /></template>
