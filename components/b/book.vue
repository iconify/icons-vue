<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6vrkhjbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f6vrkhjbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:book" /></template>
