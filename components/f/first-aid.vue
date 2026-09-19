<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zes8_9b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zes8_9b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:first-aid" /></template>
