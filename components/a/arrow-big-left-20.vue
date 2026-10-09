<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy0m3ysyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oy0m3ysyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-left-20" /></template>
