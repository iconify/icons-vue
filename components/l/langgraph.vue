<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5q1pybuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5q1pybuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:langgraph" /></template>
