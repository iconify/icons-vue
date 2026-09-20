<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvb49db5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rvb49db5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-1-story-gabled-roof" /></template>
