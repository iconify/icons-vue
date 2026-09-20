<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4d9s_b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="h4d9s_b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:day-cloudy-windy" /></template>
