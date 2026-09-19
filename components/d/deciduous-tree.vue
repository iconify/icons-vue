<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi96mobjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wi96mobjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:deciduous-tree" /></template>
