<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f86d5ub3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f86d5ub3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-right-circle-fill" /></template>
