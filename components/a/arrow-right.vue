<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8jllh0-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v8jllh0-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:arrow-right" /></template>
