<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2qeb8bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v2qeb8bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-2-story-skillion-roof" /></template>
