<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg-7rz3eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yg-7rz3eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-3-story-skillion-roof" /></template>
