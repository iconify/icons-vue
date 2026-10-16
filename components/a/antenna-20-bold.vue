<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhkwq9b2s.css';
import '../../css/h/hjfbf5arh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhkwq9b2s"/><path class="hjfbf5arh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:antenna-20-bold" /></template>
