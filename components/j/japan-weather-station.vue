<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2lgv1bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f2lgv1bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-weather-station" /></template>
