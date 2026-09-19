<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnf5dgrat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fnf5dgrat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-down-left" /></template>
