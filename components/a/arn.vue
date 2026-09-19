<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4e9x-l8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e4e9x-l8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:arn" /></template>
