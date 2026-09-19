<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j90egs33e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j90egs33e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:line-graph" /></template>
