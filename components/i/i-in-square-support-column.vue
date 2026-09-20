<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu6v7ibol.css';
import '../../css/v/vgo3iyb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mu6v7ibol"/><path class="vgo3iyb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:i-in-square-support-column" /></template>
