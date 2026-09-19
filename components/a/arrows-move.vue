<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwbp2gbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vwbp2gbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrows-move" /></template>
