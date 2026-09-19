<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymcb8gbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ymcb8gbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bar-chart-steps" /></template>
