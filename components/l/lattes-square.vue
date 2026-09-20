<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsu1dvs7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jsu1dvs7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:lattes-square" /></template>
