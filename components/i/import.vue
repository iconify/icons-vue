<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d15z4kwjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d15z4kwjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:import" /></template>
