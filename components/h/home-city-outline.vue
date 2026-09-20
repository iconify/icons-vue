<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs3sugevh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3sugevh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-city-outline" /></template>
