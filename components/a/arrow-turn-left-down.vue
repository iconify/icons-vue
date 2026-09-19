<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj3dekbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tj3dekbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-turn-left-down" /></template>
