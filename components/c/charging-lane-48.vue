<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxy5bwbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hxy5bwbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-lane-48" /></template>
