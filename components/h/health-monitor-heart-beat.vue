<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhi--6bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yhi--6bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-monitor-heart-beat" /></template>
