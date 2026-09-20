<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7_v082hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h7_v082hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:government" /></template>
