<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr6emiboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rr6emiboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:apartments-4-story-skillion-roof" /></template>
