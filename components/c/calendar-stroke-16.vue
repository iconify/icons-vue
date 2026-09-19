<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa51hjvui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aa51hjvui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:calendar-stroke-16" /></template>
