<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1lneq22n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j1lneq22n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:calendar-solid" /></template>
