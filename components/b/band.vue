<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktq03sb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ktq03sb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:band" /></template>
