<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-c7k_big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i-c7k_big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:cloud" /></template>
