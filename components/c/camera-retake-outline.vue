<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyobs_-jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyobs_-jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-retake-outline" /></template>
