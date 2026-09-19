<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydg3l3bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ydg3l3bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:3-circle-fill" /></template>
