<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4zy9ybio.css';
import '../../css/g/gw-flvwxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m4zy9ybio"/><path class="gw-flvwxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heating-schedule-20-bold" /></template>
