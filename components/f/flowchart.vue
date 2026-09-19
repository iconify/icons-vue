<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnciz5-lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rnciz5-lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:flowchart" /></template>
