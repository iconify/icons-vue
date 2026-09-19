<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6t-ros_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6t-ros_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-square-down-filled" /></template>
