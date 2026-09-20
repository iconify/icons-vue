<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_x7z-5qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="e_x7z-5qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-crossover-left" /></template>
