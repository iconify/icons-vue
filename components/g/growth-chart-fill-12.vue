<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erwi4obyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="erwi4obyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:growth-chart-fill-12" /></template>
