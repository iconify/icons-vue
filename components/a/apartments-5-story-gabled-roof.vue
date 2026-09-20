<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_-_5ac1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_-_5ac1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-5-story-gabled-roof" /></template>
