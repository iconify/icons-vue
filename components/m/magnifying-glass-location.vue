<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys4h6ub3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ys4h6ub3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:magnifying-glass-location" /></template>
