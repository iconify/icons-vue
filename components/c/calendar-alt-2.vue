<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6qjrvgox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="y6qjrvgox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:calendar-alt-2" /></template>
