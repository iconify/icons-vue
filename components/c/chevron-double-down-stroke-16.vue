<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c056y0bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c056y0bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-down-stroke-16" /></template>
