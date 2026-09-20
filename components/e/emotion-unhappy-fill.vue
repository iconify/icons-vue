<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jicddrs_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jicddrs_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-unhappy-fill" /></template>
